---
title: CaptionsCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: เป็นตัวแทนของคอลเลกชันของคำบรรยายปิด.
type: docs
url: /th/com.aspose.slides/captionscollection/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่นำมาใช้:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

เป็นตัวแทนของคอลเลกชันของคำบรรยายปิด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the closed captions at the specified index. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Adds WebVTT closed captions to the end of the collection. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Adds WebVTT closed captions to the end of the collection from a stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Removes the specified closed captions from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the closed captions at the specified index. |
| [clear()](#clear--) | Removes all closed captions from the collection. |
| [getCount()](#getCount--) | Returns the number of elements in the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

คืนคำบรรยายปิดที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ICaptions](../../com.aspose.slides/icaptions).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

Adds WebVTT closed captions to the end of the collection.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | java.lang.String | The label of the closed captions. |
| filePath | java.lang.String | The path to the WebVTT file. |

**คืนค่า:**
[ICaptions](../../com.aspose.slides/icaptions) - อินสแตนซ์ [ICaptions](../../com.aspose.slides/icaptions) ที่เพิ่ม
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Adds WebVTT closed captions to the end of the collection from a stream.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| label | java.lang.String | The label of the closed captions. |
| stream | java.io.InputStream | The input stream containing data in WebVTT format. |

**คืนค่า:**
[ICaptions](../../com.aspose.slides/icaptions) - อินสแตนซ์ [ICaptions](../../com.aspose.slides/icaptions) ที่เพิ่ม
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Removes the specified closed captions from the collection.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | The closed captions to remove. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Removes the closed captions at the specified index.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | The index of the closed captions to remove. |

### clear() {#clear--}
```
public final void clear()
```

Removes all closed captions from the collection.

### getCount() {#getCount--}
```
public final int getCount()
```

คืนจำนวนขององค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว int .

**คืนค่า:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Returns an enumerator that iterates through the collection.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - System.Collections.Generic.IEnumerator1 ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.