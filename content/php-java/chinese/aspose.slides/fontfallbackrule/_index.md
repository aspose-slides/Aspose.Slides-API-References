---
title: FontFallBackRule
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/fontfallbackrule/
---
## FontFallBackRule 类

 Represents font fallback rule
 
### FontFallBackRule {#FontFallBackRule}

| 名称 | 描述 |
| --- | --- |
| FontFallBackRule(long, long, String) | 创建新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | long | Unicode 范围的起始索引 |
| endIndex | long | Unicode 范围的结束索引 |
| fontNames | String | 用于回退的字体名称或多个名称（逗号分隔） |

 **返回:**
FontFallBackRule


---


### FontFallBackRule {#FontFallBackRule}

| 名称 | 描述 |
| --- | --- |
| FontFallBackRule(long, long, java.lang.String[]) | 创建新实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | long | Unicode 范围的起始索引 |
| endIndex | long | Unicode 范围的结束索引 |
| fontNames | java.lang.String[] | 用于回退的字体名称或多个名称（逗号分隔） |

 **返回:**
FontFallBackRule


---


### addFallBackFonts {#addFallBackFonts}

| 名称 | 描述 |
| --- | --- |
| addFallBackFonts (String) | 向回退字体列表中添加新的字体。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 用于回退的字体名称或多个名称（逗号分隔） |

 **返回:**
void


---


### addFallBackFonts {#addFallBackFonts}

| 名称 | 描述 |
| --- | --- |
| addFallBackFonts (java.lang.String[]) | 向回退字体列表中添加新的字体。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fontNames | java.lang.String[] | 用于回退的字体名称或多个名称（逗号分隔） |

 **返回:**
void


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从列表中移除所有字体。 |

 **返回:**
void


---


### getCount {#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount () | 获取在范围内实际定义的字体数量。只读 int。 |

 **返回:**
int


---


### getRangeEndIndex {#getRangeEndIndex}

| 名称 | 描述 |
| --- | --- |
| getRangeEndIndex () | 获取连续 Unicode 范围的最后索引。 |

 **返回:**
long


---


### getRangeStartIndex {#getRangeStartIndex}

| 名称 | 描述 |
| --- | --- |
| getRangeStartIndex () | 获取连续 Unicode 范围的第一个索引。 |

 **返回:**
long


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的字体名称。只读 IFontFallBackRule。 |

 **返回:**
String


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf (String) | 返回集合中指定规则的索引。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 要查找的字体名称。 |

 **返回:**
int


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove (String) | 从列表中移除首次出现的特定回退字体。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 要从列表中移除的字体名称。 |

 **返回:**
void


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 从列表中移除指定索引处的回退字体。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的字体的零基索引。 |

 **返回:**
void


---


### setRangeEndIndex {#setRangeEndIndex}

| 名称 | 描述 |
| --- | --- |
| setRangeEndIndex (long) | 获取连续 Unicode 范围的最后索引。 |

 **返回:**
void


---


### setRangeStartIndex {#setRangeStartIndex}

| 名称 | 描述 |
| --- | --- |
| setRangeStartIndex (long) | 获取连续 Unicode 范围的第一个索引。 |

 **返回:**
void


---


### toArray {#toArray}

| 名称 | 描述 |
| --- | --- |
| toArray () | 创建并返回包含此规则所有回退字体的数组。 |

 **返回:**
String


---


### toArray {#toArray}

| 名称 | 描述 |
| --- | --- |
| toArray (int, int) | 创建并返回列表中指定范围内所有回退字体的数组。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要添加的第一个字体的索引。 |
| count | int | 要添加的字体数量。 |

 **返回:**
String


---