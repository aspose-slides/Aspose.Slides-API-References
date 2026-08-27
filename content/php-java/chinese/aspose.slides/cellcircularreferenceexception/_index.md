---
title: CellCircularReferenceException
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/cellcircularreferenceexception/
---
## CellCircularReferenceException 类

 抛出此异常是因为检测到一个或多个循环引用，其中公式直接或间接地引用了它自己的单元格。

### CellCircularReferenceException {#CellCircularReferenceException}

| 名称 | 描述 |
| --- | --- |
| CellCircularReferenceException() | 初始化 CellCircularReferenceException 类的新实例。 |

 **返回:**
CellCircularReferenceException


---

### CellCircularReferenceException {#CellCircularReferenceException}

| 名称 | 描述 |
| --- | --- |
| CellCircularReferenceException(String) | 使用指定的错误消息初始化 CellCircularReferenceException 类的新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 描述错误的字符串。 |

 **返回:**
CellCircularReferenceException


---

### CellCircularReferenceException {#CellCircularReferenceException}

| 名称 | 描述 |
| --- | --- |
| CellCircularReferenceException(String, RuntimeException) | 使用指定的错误消息和指向导致此异常的内部异常的引用来初始化 CellCircularReferenceException 类的新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 描述错误的字符串。 |
| innerException | RuntimeException | 导致当前异常的内部异常。 |

 **返回:**
CellCircularReferenceException


---

### CellCircularReferenceException {#CellCircularReferenceException}

| 名称 | 描述 |
| --- | --- |
| CellCircularReferenceException(String, String) | 使用指定的错误消息和循环的单元格引用来初始化 CellCircularReferenceException 类的新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 描述错误的字符串。 |
| reference | String | 循环的单元格引用。 |

 **返回:**
CellCircularReferenceException


---

### getReference {#getReference}

| 名称 | 描述 |
| --- | --- |
| getReference () | 获取循环的单元格引用。 |

 **返回:**
String


---