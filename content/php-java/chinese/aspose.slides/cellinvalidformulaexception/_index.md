---
title: CellInvalidFormulaException
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/cellinvalidformulaexception/
---
## CellInvalidFormulaException 类

 The exception that is thrown when a calculated formula is not correct or was not parsed. 
 
### CellInvalidFormulaException {#CellInvalidFormulaException}

| 名称 | 描述 |
| --- | --- |
| CellInvalidFormulaException() | 初始化 CellInvalidFormulaException 类的新实例。 |

 **返回值:**
CellInvalidFormulaException


---


### CellInvalidFormulaException {#CellInvalidFormulaException}

| 名称 | 描述 |
| --- | --- |
| CellInvalidFormulaException(String) | 使用指定的错误消息初始化 CellInvalidFormulaException 类的新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 描述错误的字符串。 |

 **返回值:**
CellInvalidFormulaException


---


### CellInvalidFormulaException {#CellInvalidFormulaException}

| 名称 | 描述 |
| --- | --- |
| CellInvalidFormulaException(String, RuntimeException) | 使用指定的错误消息和指向导致此异常的内部异常的引用初始化 CellInvalidFormulaException 类的新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 描述错误的字符串。 |
| innerException | RuntimeException | 导致当前异常的内部异常。 |

 **返回值:**
CellInvalidFormulaException


---


### CellInvalidFormulaException {#CellInvalidFormulaException}

| 名称 | 描述 |
| --- | --- |
| CellInvalidFormulaException(String, String) | 使用指定的错误消息和包含无效公式的单元格引用初始化 CellInvalidFormulaException 类的新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| message | String | 描述错误的字符串。 |
| reference | String | 描述对内部异常的引用的字符串。 |

 **返回值:**
CellInvalidFormulaException


---


### getReference {#getReference}

| 名称 | 描述 |
| --- | --- |
| getReference () | 获取包含无效公式的单元格引用。 |

 **返回值:**
String


---