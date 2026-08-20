---
title: IDataLabelFormat
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.
type: docs
url: /th/com.aspose.slides/idatalabelformat/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

เป็นตัวแทนของตัวเลือกการจัดรูปแบบสำหรับ DataLabel.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | อ่าน/เขียน boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | อ่าน/เขียน boolean. |
| [getNumberFormat()](#getNumberFormat--) | เป็นตัวแทนของสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | เป็นตัวแทนของสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. |
| [getFormat()](#getFormat--) | เป็นตัวแทนของรูปแบบของป้ายข้อมูล. |
| [getPosition()](#getPosition--) | เป็นตัวแทนของตำแหน่งของป้ายข้อมูล. |
| [setPosition(int value)](#setPosition-int-) | เป็นตัวแทนของตำแหน่งของป้ายข้อมูล. |
| [getShowLegendKey()](#getShowLegendKey--) | เป็นตัวแทนของพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิกำหนด. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | เป็นตัวแทนของพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิกำหนด. |
| [getShowValue()](#getShowValue--) | เป็นตัวแทนของพฤติกรรมการแสดงค่าเปอร์เซ็นต์ของป้ายข้อมูลในแผนภูมิกำหนด. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | เป็นตัวแทนของพฤติกรรมการแสดงค่าเปอร์เซ็นต์ของป้ายข้อมูลในแผนภูมิกำหนด. |
| [getShowCategoryName()](#getShowCategoryName--) | เป็นตัวแทนของพฤติกรรมการแสดงชื่อประเภทของป้ายข้อมูลในแผนภูมิกำหนด. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | เป็นตัวแทนของพฤติกรรมการแสดงชื่อประเภทของป้ายข้อมูลในแผนภูมิกำหนด. |
| [getShowSeriesName()](#getShowSeriesName--) | คืนค่า หรือ กำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | คืนค่า หรือ กำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [getShowPercentage()](#getShowPercentage--) | เป็นตัวแทนของพฤติกรรมการแสดงค่าเปอร์เซ็นต์ของป้ายข้อมูลในแผนภูมิกำหนด. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | เป็นตัวแทนของพฤติกรรมการแสดงค่าเปอร์เซ็นต์ของป้ายข้อมูลในแผนภูมิกำหนด. |
| [getShowBubbleSize()](#getShowBubbleSize--) | เป็นตัวแทนของพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิกำหนด. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | เป็นตัวแทนของพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิกำหนด. |
| [getShowLeaderLines()](#getShowLeaderLines--) | เป็นตัวแทนของพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิกำหนด. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | เป็นตัวแทนของพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิกำหนด. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | กำหนดว่าป้ายข้อมูลของแผนภูมิกำหนดจะถูกแสดงเป็นการอธิบายข้อมูลหรือเป็นป้ายข้อมูล. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | กำหนดว่าป้ายข้อมูลของแผนภูมิกำหนดจะถูกแสดงเป็นการอธิบายข้อมูลหรือเป็นป้ายข้อมูล. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | เป็นตัวแทนของพฤติกรรมการแสดงค่าตำแหน่งเซลล์ของป้ายข้อมูลในแผนภูมิกำหนด. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | เป็นตัวแทนของพฤติกรรมการแสดงค่าตำแหน่งเซลล์ของป้ายข้อมูลในแผนภูมิกำหนด. |
| [getSeparator()](#getSeparator--) | กำหนดหรือคืนค่า Variant ที่เป็นตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | กำหนดหรือคืนค่า Variant ที่เป็นตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

อ่าน/เขียน boolean.

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ IsNumberFormatLinkedToSource ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);"` ทำให้ `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` ทั้งหมดมีค่าเท่ากับ val)

**คืนค่า:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

อ่าน/เขียน boolean.

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ IsNumberFormatLinkedToSource ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);"` ทำให้ `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` ทั้งหมดมีค่าเท่ากับ val)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

เป็นตัวแทนของสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. อ่าน/เขียน String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
```

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection เมื่อกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่ง ค่านั้นจะถูกตั้งค่าให้กับคุณสมบัติ NumberFormat ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);"` ทำให้ `DataLabels.get_Item(i).getNumberFormat()` ทั้งหมดมีค่าเท่ากับ val)

**คืนค่า:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

เป็นตัวแทนของสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. อ่าน/เขียน String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
```

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection เมื่อกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่ง ค่านั้นจะถูกตั้งค่าให้กับคุณสมบัติ NumberFormat ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);"` ทำให้ `DataLabels.get_Item(i).getNumberFormat()` ทั้งหมดมีค่าเท่ากับ val)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

เป็นตัวแทนของรูปแบบของป้ายข้อมูล. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้เป็นรูปแบบปริยายสำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

เป็นตัวแทนของตำแหน่งของป้ายข้อมูล. อ่าน/เขียน [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ Position สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection เป็นตำแหน่งสำหรับอ็อบเจกต์ DataLabel การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ Position ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setPosition(val)"` ทำให้ `DataLabels.get_Item(i).getPosition()` ทั้งหมดมีค่าเท่ากับ val)

**คืนค่า:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

เป็นตัวแทนของตำแหน่งของป้ายข้อมูล. อ่าน/เขียน [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ Position สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection เป็นตำแหน่งสำหรับอ็อบเจกต์ DataLabel การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ Position ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setPosition(val)"` ทำให้ `DataLabels.get_Item(i).getPosition()` ทั้งหมดมีค่าเท่ากับ val)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

เป็นตัวแทนของพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิกำหนด. true หากคีย์คำอธิบายของป้ายข้อมูลเป็นที่มองเห็นได้. อ่าน/เขียน boolean.

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowLegendKey สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ ShowLegendKey ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);"` ทำให้ `DataLabels.get_Item(i).getShowLegendKey()` ทั้งหมดมีค่าเท่ากับ val)

**คืนค่า:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

เป็นตัวแทนของพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิกำหนด. true หากคีย์คำอธิบายของป้ายข้อมูลเป็นที่มองเห็นได้. อ่าน/เขียน boolean.

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowLegendKey สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ ShowLegendKey ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);"` ทำให้ `DataLabels.get_Item(i).getShowLegendKey()` ทั้งหมดมีค่าเท่ากับ val)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

เป็นตัวแทนของพฤติกรรมการแสดงค่าเปอร์เซ็นต์ของป้ายข้อมูลในแผนภูมิกำหนด. true เพื่อแสดงค่าเปอร์เซ็นต์. false เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowValue สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ ShowValue ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setShowValue(val);"` ทำให้ `DataLabels.get_Item(i).getShowValue()` ทั้งหมดมีค่าเท่ากับ val)

**คืนค่า:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

เป็นตัวแทนของพฤติกรรมการแสดงค่าเปอร์เซ็นต์ของป้ายข้อมูลในแผนภูมิกำหนด. true เพื่อแสดงค่าเปอร์เซ็นต์. false เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowValue สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ ShowValue ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setShowValue(val);"` ทำให้ `DataLabels.get_Item(i).getShowValue()` ทั้งหมดมีค่าเท่ากับ val)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

เป็นตัวแทนของพฤติกรรมการแสดงชื่อประเภทของป้ายข้อมูลในแผนภูมิกำหนด. true เพื่อแสดงชื่อประเภทสำหรับป้ายข้อมูลบนแผนภูมิ. false เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนท์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowCategoryName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ ShowCategoryName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น `"DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);"` ทำให้ `DataLabels.get_Item(i).getShowCategoryName()` ทั้งหมดมีค่าเท่ากับ val)

**คืนค่า:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

เป็นตัวแทนของพฤติกรรมการแสดงชื่อประเภทของป้ายข้อมูลในแผนภูมิกำหนด. true เพื่อแสดงชื่อประเภทสำหรับป้ายข้อมูลบนแผนภูมิ. false เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------
หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowCategoryName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowCategoryName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ทำให้ DataLabels.get_Item(i).getShowCategoryName() ทั้งหมดเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

ส่งคืนหรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ ค่า true เพื่อแสดงชื่อซีรีส์ ค่า false เพื่อซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowSeriesName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowSeriesName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ทำให้ DataLabels.get_Item(i).getShowSeriesName() ทั้งหมดเท่ากับ val).

**ส่งคืน:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

ส่งคืนหรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ ค่า true เพื่อแสดงชื่อซีรีส์ ค่า false เพื่อซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowSeriesName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowSeriesName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ทำให้ DataLabels.get_Item(i).getShowSeriesName() ทั้งหมดเท่ากับ val).

**พараมิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิกำหนดไว้ ค่า true แสดงค่าร้อยละ ค่า false ซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowPercentage สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowPercentage ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ทำให้ DataLabels.get_Item(i).getShowPercentage() ทั้งหมดเท่ากับ val).

**ส่งคืน:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิกำหนดไว้ ค่า true แสดงค่าร้อยละ ค่า false ซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowPercentage สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowPercentage ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ทำให้ DataLabels.get_Item(i).getShowPercentage() ทั้งหมดเท่ากับ val).

**พараมิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิกำหนดไว้ ค่า true แสดงค่าขนาดฟอง ค่า false ซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowBubbleSize สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowBubbleSize ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ทำให้ DataLabels.get_Item(i).getShowBubbleSize() ทั้งหมดเท่ากับ val).

**ส่งคืน:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิกำหนดไว้ ค่า true แสดงค่าขนาดฟอง ค่า false ซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowBubbleSize สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowBubbleSize ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ทำให้ DataLabels.get_Item(i).getShowBubbleSize() ทั้งหมดเท่ากับ val).

**พараมิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิกำหนดไว้ ค่า true แสดงเส้นนำ ค่า false ซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowLeaderLines สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowLeaderLines ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ทำให้ DataLabels.get_Item(i).getShowLeaderLines() ทั้งหมดเท่ากับ val).

**ส่งคืน:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิกำหนดไว้ ค่า true แสดงเส้นนำ ค่า false ซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowLeaderLines สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowLeaderLines ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ทำให้ DataLabels.get_Item(i).getShowLeaderLines() ทั้งหมดเท่ากับ val).

**พараมิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

กำหนดว่าป้ายข้อมูลของแผนภูมิกำหนดจะถูกแสดงเป็นข้อมูลเรียกเข้าหรือเป็นป้ายข้อมูลทั่วไป.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowLabelAsDataCallout ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ทำให้ DataLabels.get_Item(i).getShowLabelAsDataCallout() ทั้งหมดเท่ากับ val).

**ส่งคืน:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

กำหนดว่าป้ายข้อมูลของแผนภูมิกำหนดจะถูกแสดงเป็นข้อมูลเรียกเข้าหรือเป็นป้ายข้อมูลทั่วไป.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowLabelAsDataCallout ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ทำให้ DataLabels.get_Item(i).getShowLabelAsDataCallout() ทั้งหมดเท่ากับ val).

**พараมิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

แสดงพฤติกรรมการแสดงค่าจากเซลล์ของป้ายข้อมูลในแผนภูมิกำหนดไว้ ค่า true แสดงค่าจากเซลล์ ค่า false ซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowLabelValueFromCell สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowLabelValueFromCell ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ทำให้ DataLabels.get_Item(i).getShowLabelValueFromCell() ทั้งหมดเท่ากับ val).

**ส่งคืน:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

แสดงพฤติกรรมการแสดงค่าจากเซลล์ของป้ายข้อมูลในแผนภูมิกำหนดไว้ ค่า true แสดงค่าจากเซลล์ ค่า false ซ่อน อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ ShowLabelValueFromCell สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ ShowLabelValueFromCell ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ทำให้ DataLabels.get_Item(i).getShowLabelValueFromCell() ทั้งหมดเท่ากับ val).

**พараมิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

ตั้งค่าหรือรับค่า Variant ที่เป็นตัวคั่นที่ใช้สำหรับป้ายข้อมูลในแผนภูมิ อ่าน/เขียน String.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ Separator สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ Separator ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ทำให้ DataLabels.get_Item(i).getSeparator() ทั้งหมดเท่ากับ val).

**ส่งคืน:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

ตั้งค่า或รับค่า Variant ที่เป็นตัวคั่นที่ใช้สำหรับป้ายข้อมูลในแผนภูมิ อ่าน/เขียน String.

--------------------

หากพาเรนต์ของวัตถุ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตัวเริ่มต้นของคุณสมบัติ Separator สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ค่าที่ตั้งให้กับคุณสมบัตินี้ยังกำหนดค่าเดียวกันให้กับคุณสมบัติ Separator ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ทำให้ DataLabels.get_Item(i).getSeparator() ทั้งหมดเท่ากับ val).
**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |