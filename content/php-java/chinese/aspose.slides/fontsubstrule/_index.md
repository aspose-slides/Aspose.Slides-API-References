---
title: FontSubstRule
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/fontsubstrule/
---
## FontSubstRule 类

 表示字体替换信息
 
### FontSubstRule {#FontSubstRule}

| 名称 | 描述 |
| --- | --- |
| FontSubstRule([FontData](../fontdata), [FontData](../fontdata)) | 创建新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | 源字体。 |
| destFont | [FontData](../fontdata) | 目标字体。 |

 **返回:**
FontSubstRule


---


### FontSubstRule {#FontSubstRule}

| 名称 | 描述 |
| --- | --- |
| FontSubstRule([FontData](../fontdata), [FontData](../fontdata), int) | 创建新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | 源字体。 |
| destFont | [FontData](../fontdata) | 目标字体。 |
| fontSubstRule | int | 字体替换规则。 |

 **返回:**
FontSubstRule


---


### getDestFont {#getDestFont}

| 名称 | 描述 |
| --- | --- |
| getDestFont () | 用于替换的字体。只读 IFontData。 |

 **返回:**
[FontData](../fontdata)


---


### getReplaceFontCondition {#getReplaceFontCondition}

| 名称 | 描述 |
| --- | --- |
| getReplaceFontCondition () | 用于替换的规则。只读 FontSubstCondition。 |

 **返回:**
int


---


### getSourceFont {#getSourceFont}

| 名称 | 描述 |
| --- | --- |
| getSourceFont () | 要替换的字体。只读 IFontData。 |

 **返回:**
[FontData](../fontdata)


---