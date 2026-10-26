---
title: DataLabelFormat
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.
type: docs
url: /th/com.aspose.slides/datalabelformat/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)  
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Represents formatting options for DataLabel.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | อ่าน/เขียน boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | อ่าน/เขียน boolean. |
| [getNumberFormat()](#getNumberFormat--) | แสดงสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | แสดงสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของป้ายข้อมูล. |
| [getPosition()](#getPosition--) | แสดงตำแหน่งของป้ายข้อมูล. |
| [setPosition(int value)](#setPosition-int-) | แสดงตำแหน่งของป้ายข้อมูล. |
| [getShowLegendKey()](#getShowLegendKey--) | แสดงพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | แสดงพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowValue()](#getShowValue--) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowCategoryName()](#getShowCategoryName--) | แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowSeriesName()](#getShowSeriesName--) | ส่งคืนหรือกำหนดค่า Boolean เพื่อบ่งชี้พฤติกรรมการแสดงชื่อชุดข้อมูลสำหรับป้ายข้อมูลในแผนภูมิ. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | ส่งคืนหรือกำหนดค่า Boolean เพื่อบ่งชี้พฤติกรรมการแสดงชื่อชุดข้อมูลสำหรับป้ายข้อมูลในแผนภูมิ. |
| [getShowPercentage()](#getShowPercentage--) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowBubbleSize()](#getShowBubbleSize--) | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowLeaderLines()](#getShowLeaderLines--) | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | แสดงพฤติกรรมการแสดงค่าเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | แสดงพฤติกรรมการแสดงค่าเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นการอ้างอิงข้อมูลหรือเป็นป้ายข้อมูล. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นการอ้างอิงข้อมูลหรือเป็นป้ายข้อมูล. |
| [getSeparator()](#getSeparator--) | กำหนดหรือส่งคืน Variant ที่แทนค่าตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | กำหนดหรือส่งคืน Variant ที่แทนค่าตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [getTextFormat()](#getTextFormat--) | ส่งคืนรูปแบบข้อความของแผนภูมิ. |
| [getChart()](#getChart--) | ส่งคืนแผนภูมิ. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

รุ่น. อ่านอย่างเดียว long.

**ส่งคืน:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" ทำให้ DataLabels.get_Item(i).isNumberFormatLinkedToSource() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" ทำให้ DataLabels.get_Item(i).isNumberFormatLinkedToSource() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

แสดงสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. อ่าน/เขียน String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. เมื่อกำหนดค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าให้กับคุณสมบัติ NumberFormat ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" ทำให้ DataLabels.get_Item(i).getNumberFormat() มีค่าเท่ากับ val).

**ส่งคืน:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

แสดงสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. อ่าน/เขียน String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. เมื่อกำหนดค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าให้กับคุณสมบัติ NumberFormat ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" ทำให้ DataLabels.get_Item(i).getNumberFormat() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

แสดงรูปแบบของป้ายข้อมูล. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้แสดงรูปแบบตั้งต้นสำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection.

**ส่งคืน:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

แสดงตำแหน่งของป้ายข้อมูล. อ่าน/เขียน [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Position สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. แสดงตำแหน่งของอ็อบเจกต์ DataLabel. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ Position ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setPosition(val);" ทำให้ DataLabels.get_Item(i).getPosition() มีค่าเท่ากับ val).

**ส่งคืน:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

แสดงตำแหน่งของป้ายข้อมูล. อ่าน/เขียน [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Position สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. แสดงตำแหน่งของอ็อบเจกต์ DataLabel. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ Position ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setPosition(val);" ทำให้ DataLabels.get_Item(i).getPosition() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

แสดงพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิที่ระบุ. True ถ้าคีย์คำอธิบายของป้ายข้อมูลแสดงผล. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLegendKey สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowLegendKey ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" ทำให้ DataLabels.get_Item(i).getShowLegendKey() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

แสดงพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิที่ระบุ. True ถ้าคีย์คำอธิบายของป้ายข้อมูลแสดงผล. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLegendKey สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowLegendKey ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" ทำให้ DataLabels.get_Item(i).getShowLegendKey() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowValue สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowValue ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" ทำให้ DataLabels.get_Item(i).getShowValue() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowValue สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowValue ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" ทำให้ DataLabels.get_Item(i).getShowValue() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิที่ระบุ. True เพื่อแสดงชื่อหมวดหมู่สำหรับป้ายข้อมูลในแผนภูมิ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowCategoryName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowCategoryName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ทำให้ DataLabels.get_Item(i).getShowCategoryName() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิที่ระบุ. True เพื่อแสดงชื่อหมวดหมู่สำหรับป้ายข้อมูลในแผนภูมิ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowCategoryName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowCategoryName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ทำให้ DataLabels.get_Item(i).getShowCategoryName() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

ส่งคืนหรือกำหนดค่า Boolean เพื่อบ่งชี้พฤติกรรมการแสดงชื่อชุดข้อมูลสำหรับป้ายข้อมูลในแผนภูมิ. True เพื่อแสดงชื่อชุดข้อมูล. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowSeriesName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowSeriesName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ทำให้ DataLabels.get_Item(i).getShowSeriesName() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

ส่งคืนหรือกำหนดค่า Boolean เพื่อบ่งชี้พฤติกรรมการแสดงชื่อชุดข้อมูลสำหรับป้ายข้อมูลในแผนภูมิ. True เพื่อแสดงชื่อชุดข้อมูล. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowSeriesName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowSeriesName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ทำให้ DataLabels.get_Item(i).getShowSeriesName() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowPercentage สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowPercentage ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ทำให้ DataLabels.get_Item(i).getShowPercentage() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowPercentage สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowPercentage ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ทำให้ DataLabels.get_Item(i).getShowPercentage() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าขนาดฟอง. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowBubbleSize สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowBubbleSize ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ทำให้ DataLabels.get_Item(i).getShowBubbleSize() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าขนาดฟอง. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowBubbleSize สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowBubbleSize ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ทำให้ DataLabels.get_Item(i).getShowBubbleSize() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงเส้นนำ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLeaderLines สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowLeaderLines ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ทำให้ DataLabels.get_Item(i).getShowLeaderLines() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงเส้นนำ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLeaderLines สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowLeaderLines ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ทำให้ DataLabels.get_Item(i).getShowLeaderLines() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

แสดงพฤติกรรมการแสดงค่าเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าเซลล์. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelValueFromCell สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowLabelValueFromCell ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ทำให้ DataLabels.get_Item(i).getShowLabelValueFromCell() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

แสดงพฤติกรรมการแสดงค่าเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าเซลล์. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelValueFromCell สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowLabelValueFromCell ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ทำให้ DataLabels.get_Item(i).getShowLabelValueFromCell() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นการอ้างอิงข้อมูลหรือเป็นป้ายข้อมูล.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowLabelAsDataCallout ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ทำให้ DataLabels.get_Item(i).getShowLabelAsDataCallout() มีค่าเท่ากับ val).

**ส่งคืน:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นการอ้างอิงข้อมูลหรือเป็นป้ายข้อมูล.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ ShowLabelAsDataCallout ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ทำให้ DataLabels.get_Item(i).getShowLabelAsDataCallout() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

กำหนดหรือส่งคืน Variant ที่แทนค่าตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. อ่าน/เขียน String.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Separator สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ Separator ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ทำให้ DataLabels.get_Item(i).getSeparator() มีค่าเท่ากับ val).

**ส่งคืน:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

กำหนดหรือส่งคืน Variant ที่แทนค่าตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. อ่าน/เขียน String.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Separator สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ จะกำหนดค่านี้ให้กับคุณสมบัติ Separator ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ทำให้ DataLabels.get_Item(i).getSeparator() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

ส่งคืนรูปแบบข้อความของแผนภูมิ. อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**ส่งคืน:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

ส่งคืนแผนภูมิ. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**ส่งคืน:**
[IChart](../../com.aspose.slides/ichart)