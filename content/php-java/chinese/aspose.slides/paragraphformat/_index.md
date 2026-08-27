---
title: ParagraphFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/paragraphformat/
---
## ParagraphFormat 类

 此类包含段落格式属性。与 IParagraphFormatEffectiveData 不同，此类的所有属性均可写。  
 此类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到“未定义”的值。若需获取包括继承在内的有效格式参数值，需要使用 ParagraphFormat#getEffective 方法，该方法返回一个 IParagraphFormatEffectiveData 实例。

### ParagraphFormat {#ParagraphFormat}

| 名称 | 描述 |
| --- | --- |
| ParagraphFormat() | 初始化 ParagraphFormat 类的新实例。 |

**返回:**  
ParagraphFormat


---


### getAlignment {#getAlignment}

| 名称 | 描述 |
| --- | --- |
| getAlignment () | 返回或设置段落中文本对齐方式，未应用继承。 可读写 TextAlignment。 |

**返回:**  
int


---


### getBullet {#getBullet}

| 名称 | 描述 |
| --- | --- |
| getBullet () | 返回段落的项目符号格式。 只读 IBulletFormat。 |

**返回:**  
[BulletFormat](../bulletformat)


---


### getDefaultPortionFormat {#getDefaultPortionFormat}

| 名称 | 描述 |
| --- | --- |
| getDefaultPortionFormat () | 返回段落的默认部分格式。未应用继承。 只读 IPortionFormat。 |

**返回:**  
[PortionFormat](../portionformat)


---


### getDefaultTabSize {#getDefaultTabSize}

| 名称 | 描述 |
| --- | --- |
| getDefaultTabSize () | 返回或设置默认制表符大小，未应用继承。 可读写 float。 |

**返回:**  
float


---


### getDepth {#getDepth}

| 名称 | 描述 |
| --- | --- |
| getDepth () | 返回或设置段落的深度。值 0 表示未定义。 可读写 short。 |

**返回:**  
short


---


### getEastAsianLineBreak {#getEastAsianLineBreak}

| 名称 | 描述 |
| --- | --- |
| getEastAsianLineBreak () | 确定段落是否使用亚洲换行。未应用继承。 可读写 NullableBool。 |

**返回:**  
byte


---


### getEffective {#getEffective}

| 名称 | 描述 |
| --- | --- |
| getEffective () | 获取已应用继承的有效段落格式数据。 |

**返回:**  
ParagraphFormatEffectiveData


---


### getFontAlignment {#getFontAlignment}

| 名称 | 描述 |
| --- | --- |
| getFontAlignment () | 返回或设置段落中的字体对齐方式，未应用继承。 可读写 FontAlignment。 |

**返回:**  
int


---


### getHangingPunctuation {#getHangingPunctuation}

| 名称 | 描述 |
| --- | --- |
| getHangingPunctuation () | 确定段落是否使用悬挂标点。未应用继承。 可读写 NullableBool。 |

**返回:**  
byte


---


### getIndent {#getIndent}

| 名称 | 描述 |
| --- | --- |
| getIndent () | 返回或设置段落的首行缩进/悬挂缩进，未应用继承。负值可定义悬挂缩进。 可读写 float。 |

**返回:**  
float


---


### getLatinLineBreak {#getLatinLineBreak}

| 名称 | 描述 |
| --- | --- |
| getLatinLineBreak () | 确定段落是否使用拉丁换行。未应用继承。 可读写 NullableBool。 |

**返回:**  
byte


---


### getMarginLeft {#getMarginLeft}

| 名称 | 描述 |
| --- | --- |
| getMarginLeft () | 返回或设置段落的左侧边距，未应用继承。 可读写 float。 |

**返回:**  
float


---


### getMarginRight {#getMarginRight}

| 名称 | 描述 |
| --- | --- |
| getMarginRight () | 返回或设置段落的右侧边距，未应用继承。 可读写 float。 |

**返回:**  
float


---


### getRightToLeft {#getRightToLeft}

| 名称 | 描述 |
| --- | --- |
| getRightToLeft () | 确定段落是否使用从右到左的写法。未应用继承。 可读写 NullableBool。 |

**返回:**  
byte


---


### getSpaceAfter {#getSpaceAfter}

| 名称 | 描述 |
| --- | --- |
| getSpaceAfter () | 返回或设置段落最后一行之后的空间量，未应用继承。正值表示相对于字体大小的百分比，负值表示以点数指定的空间大小。 可读写 float。 |

**返回:**  
float


---


### getSpaceBefore {#getSpaceBefore}

| 名称 | 描述 |
| --- | --- |
| getSpaceBefore () | 返回或设置段落第一行之前的空间量，未应用继承。正值表示相对于字体大小的百分比，负值表示以点数指定的空间大小。 可读写 float。 |

**返回:**  
float


---


### getSpaceWithin {#getSpaceWithin}

| 名称 | 描述 |
| --- | --- |
| getSpaceWithin () | 返回或设置段落基线之间的间距。正值表示百分比，负值表示以点数指定的大小。未应用继承。 可读写 float。 |

**返回:**  
float


---


### getTabs {#getTabs}

| 名称 | 描述 |
| --- | --- |
| getTabs () | 返回段落的制表符集合。未应用继承。 只读 ITabCollection。 |

**返回:**  
[TabCollection](../tabcollection)


---


### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () |  |

**返回:**  
long


---


### setAlignment {#setAlignment}

| 名称 | 描述 |
| --- | --- |
| setAlignment (int) | 返回或设置段落中文本对齐方式，未应用继承。 可读写 TextAlignment。 |

**返回:**  
void


---


### setDefaultTabSize {#setDefaultTabSize}

| 名称 | 描述 |
| --- | --- |
| setDefaultTabSize (float) | 返回或设置默认制表符大小，未应用继承。 可读写 float。 |

**返回:**  
void


---


### setDepth {#setDepth}

| 名称 | 描述 |
| --- | --- |
| setDepth (short) | 返回或设置段落的深度。值 0 表示未定义。 可读写 short。 |

**返回:**  
void


---


### setEastAsianLineBreak {#setEastAsianLineBreak}

| 名称 | 描述 |
| --- | --- |
| setEastAsianLineBreak (byte) | 确定段落是否使用亚洲换行。未应用继承。 可读写 NullableBool。 |

**返回:**  
void


---


### setFontAlignment {#setFontAlignment}

| 名称 | 描述 |
| --- | --- |
| setFontAlignment (int) | 返回或设置段落中的字体对齐方式，未应用继承。 可读写 FontAlignment。 |

**返回:**  
void


---


### setHangingPunctuation {#setHangingPunctuation}

| 名称 | 描述 |
| --- | --- |
| setHangingPunctuation (byte) | 确定段落是否使用悬挂标点。未应用继承。 可读写 NullableBool。 |

**返回:**  
void


---


### setIndent {#setIndent}

| 名称 | 描述 |
| --- | --- |
| setIndent (float) | 返回或设置段落的首行缩进/悬挂缩进，未应用继承。负值可定义悬挂缩进。 可读写 float。 |

**返回:**  
void


---


### setLatinLineBreak {#setLatinLineBreak}

| 名称 | 描述 |
| --- | --- |
| setLatinLineBreak (byte) | 确定段落是否使用拉丁换行。未应用继承。 可读写 NullableBool。 |

**返回:**  
void


---


### setMarginLeft {#setMarginLeft}

| 名称 | 描述 |
| --- | --- |
| setMarginLeft (float) | 返回或设置段落的左侧边距，未应用继承。 可读写 float。 |

**返回:**  
void


---


### setMarginRight {#setMarginRight}

| 名称 | 描述 |
| --- | --- |
| setMarginRight (float) | 返回或设置段落的右侧边距，未应用继承。 可读写 float。 |

**返回:**  
void


---


### setRightToLeft {#setRightToLeft}

| 名称 | 描述 |
| --- | --- |
| setRightToLeft (byte) | 确定段落是否使用从右到左的写法。未应用继承。 可读写 NullableBool。 |

**返回:**  
void


---


### setSpaceAfter {#setSpaceAfter}

| 名称 | 描述 |
| --- | --- |
| setSpaceAfter (float) | 返回或设置段落最后一行之后的空间量，未应用继承。正值表示相对于字体大小的百分比，负值表示以点数指定的空间大小。 可读写 float。 |

**返回:**  
void


---


### setSpaceBefore {#setSpaceBefore}

| 名称 | 描述 |
| --- | --- |
| setSpaceBefore (float) | 返回或设置段落第一行之前的空间量，未应用继承。正值表示相对于字体大小的百分比，负值表示以点数指定的空间大小。 可读写 float。 |

**返回:**  
void


---


### setSpaceWithin {#setSpaceWithin}

| 名称 | 描述 |
| --- | --- |
| setSpaceWithin (float) | 返回或设置段落基线之间的间距。正值表示百分比，负值表示以点数指定的大小。未应用继承。 可读写 float。 |

**返回:**  
void


---