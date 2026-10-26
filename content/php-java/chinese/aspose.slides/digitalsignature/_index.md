---
title: DigitalSignature
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/digitalsignature/
---
## DigitalSignature 类

 Digital signature in signed file.
 
### DigitalSignature {#DigitalSignature}

| 名称 | 描述 |
| --- | --- |
| DigitalSignature(byte[], String) | 使用指定的证书创建一个新的 DigitalSignature 对象。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| certData | byte[] | 包含证书的字节数组 |
| password | String | 访问证书所需的密码。 |

 **返回：**
DigitalSignature


---


### DigitalSignature {#DigitalSignature}

| 名称 | 描述 |
| --- | --- |
| DigitalSignature(String, String) | 使用指定的证书文件路径和密码创建一个新的 DigitalSignature 对象。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 证书文件的路径。 |
| password | String | 访问证书所需的密码。 |

 **返回：**
DigitalSignature


---


### getCertificate {#getCertificate}

| 名称 | 描述 |
| --- | --- |
| getCertificate () | 用于签署文档的证书对象。只读 byte[]. |

 **返回：**
byte


---


### getComments {#getComments}

| 名称 | 描述 |
| --- | --- |
| getComments () | 签名的目的。读写 String。 |

 **返回：**
String


---


### getSignTime {#getSignTime}

| 名称 | 描述 |
| --- | --- |
| getSignTime () | 文档签署的时间。只读 java.util.Date。 |

 **返回：**
Date


---


### isValid {#isValid}

| 名称 | 描述 |
| --- | --- |
| isValid () | 如果此数字签名有效且文档未被篡改，此值将为 true。只读 boolean。 |

 **返回：**
boolean


---


### setComments {#setComments}

| 名称 | 描述 |
| --- | --- |
| setComments (String) | 签名的目的。读写 String。 |

 **返回：**
void


---