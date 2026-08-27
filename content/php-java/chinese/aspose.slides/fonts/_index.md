---
title: Fonts
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs
url: /zh/aspose.slides/fonts/
---
## Fonts 类

 Fonts 集合。

### getComplexScriptFont {#getComplexScriptFont}

| 名称 | 描述 |
| --- | --- |
| getComplexScriptFont () | 返回或设置复合脚本字体。读/写 IFontData。 |

**返回：**
[FontData](../fontdata)

---


### getEastAsianFont {#getEastAsianFont}

| 名称 | 描述 |
| --- | --- |
| getEastAsianFont () | 返回或设置东亚字体。读/写 IFontData。 |

**返回：**
[FontData](../fontdata)

---


### getLatinFont {#getLatinFont}

| 名称 | 描述 |
| --- | --- |
| getLatinFont () | 返回或设置拉丁字体。读/写 IFontData。 |

**返回：**
[FontData](../fontdata)

---


### getScriptFont {#getScriptFont}

| 名称 | 描述 |
| --- | --- |
| getScriptFont (String) | 获取演示文稿主题中与特定脚本标签关联的字体名称。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| script | String | 用于标识书写系统的 BCP-47 脚本代码（例如 “Latn”、 “Cyrl”、 “Jpan”）。 |

**返回：**
String

---


### getScriptFontMap {#getScriptFontMap}

| 名称 | 描述 |
| --- | --- |
| getScriptFontMap () | 返回演示文稿中所有脚本字体定义的字典。 |

**返回：**
Dictionary

---


### removeScriptFont {#removeScriptFont}

| 名称 | 描述 |
| --- | --- |
| removeScriptFont (String) | 从主题的字体集合中移除与特定脚本标签关联的字体设置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| script | String | 要移除其字体设置的 BCP-47 脚本代码。 |

**返回：**
void

---


### setComplexScriptFont {#setComplexScriptFont}

| 名称 | 描述 |
| --- | --- |
| setComplexScriptFont ([FontData](../fontdata)) | 返回或设置复合脚本字体。读/写 IFontData。 |

**返回：**
void

---


### setEastAsianFont {#setEastAsianFont}

| 名称 | 描述 |
| --- | --- |
| setEastAsianFont ([FontData](../fontdata)) | 返回或设置东亚字体。读/写 IFontData。 |

**返回：**
void

---


### setLatinFont {#setLatinFont}

| 名称 | 描述 |
| --- | --- |
| setLatinFont ([FontData](../fontdata)) | 返回或设置拉丁字体。读/写 IFontData。 |

**返回：**
void

---


### setScriptFont {#setScriptFont}

| 名称 | 描述 |
| --- | --- |
| setScriptFont (String, String) | 为特定脚本标签分配字体名称，以定义该脚本的文本在演示文稿中的呈现方式。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| script | String | 用于标识书写系统的 BCP-47 脚本代码（例如 “Arab”、 “Hebr”、 “Hans”）。 |
| fontName | String | 要分配给指定脚本的字体名称。 |

**返回：**
void

---