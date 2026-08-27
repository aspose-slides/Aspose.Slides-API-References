---
title: Metered
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/metered/
---
## Metered 类
提供用于设置计量密钥的方法。
### Metered {#Metered}

| 名称 | 描述 |
| --- | --- |
| Metered() | 初始化此类的新实例。 |

 **返回:**  
Metered


---


### getConsumptionCredit {#getConsumptionCredit}

| 名称 | 描述 |
| --- | --- |
| getConsumptionCredit () | 获取消费信用 |

 **返回:**  
double


---


### getConsumptionQuantity {#getConsumptionQuantity}

| 名称 | 描述 |
| --- | --- |
| getConsumptionQuantity () | 获取消费文件大小 |

 **返回:**  
double


---


### isMeteredLicensed {#isMeteredLicensed}

| 名称 | 描述 |
| --- | --- |
| isMeteredLicensed () | 检查计量是否已授权 |

 **返回:**  
boolean


---


### setMeteredKey {#setMeteredKey}

| 名称 | 描述 |
| --- | --- |
| setMeteredKey (String, String) | 设置计量公共和私有密钥。如果购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。然而，如果始终无法上传消费数据且超过 24 小时，许可证将被设置为评估状态。为避免此情况，应定期检查许可证状态；如果为评估状态，请再次调用此 API。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | String | public key |
| privateKey | String | private key |

 **返回:**  
void


---