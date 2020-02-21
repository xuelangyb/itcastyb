# itcastyb
adasdad
{
	"info": {
		"_postman_id": "1f54844f-f81f-4dad-8964-176d327ee1c9",
		"name": "法律API",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "律师",
			"item": [
				{
					"name": "律师案由分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/caseList.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"caseList.action",
								"74525"
							]
						}
					},
					"response": []
				},
				{
					"name": "律师案件类型分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/typeList.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"typeList.action",
								"74525"
							]
						}
					},
					"response": []
				},
				{
					"name": "律师法院层级分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/courtLevelList.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"courtLevelList.action",
								"74525"
							]
						}
					},
					"response": []
				},
				{
					"name": "律师案件时间分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/timeList.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"timeList.action",
								"74525"
							]
						}
					},
					"response": []
				},
				{
					"name": "律师案件地区分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/placeList.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"placeList.action",
								"74525"
							]
						}
					},
					"response": []
				},
				{
					"name": "律师诉讼阶段分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/phaseList.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"phaseList.action",
								"74525"
							]
						}
					},
					"response": []
				},
				{
					"name": "律师客户类型分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/customerType.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"customerType.action",
								"74525"
							]
						}
					},
					"response": []
				},
				{
					"name": "律师判决胜诉率",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/sentence.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"sentence.action",
								"74525"
							]
						}
					},
					"response": []
				},
				{
					"name": "律师判决标的额分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/lawFirm/sentenceCount.action/74525",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"lawFirm",
								"sentenceCount.action",
								"74525"
							]
						}
					},
					"response": []
				}
			],
			"protocolProfileBehavior": {}
		},
		{
			"name": "当事人",
			"item": [
				{
					"name": "当事人案由分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/party/getApiAnyu.action/51167",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"party",
								"getApiAnyu.action",
								"51167"
							]
						}
					},
					"response": []
				},
				{
					"name": "当事人案件类型分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/party/getApiType.action/51167",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"party",
								"getApiType.action",
								"51167"
							]
						}
					},
					"response": []
				},
				{
					"name": "当事人法院层级分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/party/getApiCourtLevel.action/51167",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"party",
								"getApiCourtLevel.action",
								"51167"
							]
						}
					},
					"response": []
				},
				{
					"name": "当事人案件时间分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/party/getApiTime.action/51167",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"party",
								"getApiTime.action",
								"51167"
							]
						}
					},
					"response": []
				},
				{
					"name": "当事人案件地区分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/party/getApiRegion.action/51167",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"party",
								"getApiRegion.action",
								"51167"
							]
						}
					},
					"response": []
				},
				{
					"name": "当事人判决标的额分布",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/party/getApiBde.action/51167",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"party",
								"getApiBde.action",
								"51167"
							]
						}
					},
					"response": []
				},
				{
					"name": "当事人判决胜诉率",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://47.104.3.204:8080/lawforcomsaas/api/party/getApiSsl.action/51167",
							"protocol": "http",
							"host": [
								"47",
								"104",
								"3",
								"204"
							],
							"port": "8080",
							"path": [
								"lawforcomsaas",
								"api",
								"party",
								"getApiSsl.action",
								"51167"
							]
						}
					},
					"response": []
				}
			],
			"protocolProfileBehavior": {}
		}
	],
	"protocolProfileBehavior": {}
}
