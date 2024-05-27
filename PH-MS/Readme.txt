PH-MS数据集含Phoenix市签到数据168,574条，Mesa市签到数据20,966条。
每一条签到记录的格式为：
{"business_id": "xx", "city": "xx", "latitude": xx, "longitude": xx, "review_id": "xx", "user_id": "xx", "date": "xx", "stars": xx, "categories": "xx"}，
其中，"business_id"字段表示兴趣点id、"city"字段表示所在城市（即phoenix或mesa）、"latitude"和"longitude"字段表示兴趣点的地理经纬度坐标、"review_id"字段表示当前签到记录的id、"date"字段表示签到发生的时间（如2017-12-26 18:09:29）、"stars"字段表示当前签到的用户评分（数值型），取值范围为{1.0, 2.0, 3.0, 4.0, 5.0}，"categories"字段表示当前兴趣点的类别描述。