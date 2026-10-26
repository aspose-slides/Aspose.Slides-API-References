---
title: DataLabelFormat
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.
type: docs
url: /th/com.aspose.slides/datalabelformat/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | อ่าน/เขียน boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | อ่าน/เขียน boolean. |
| [getNumberFormat()](#getNumberFormat--) | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของป้ายข้อมูล. |
| [getPosition()](#getPosition--) | แสดงตำแหน่งของป้ายข้อมูล. |
| [setPosition(int value)](#setPosition-int-) | แสดงตำแหน่งของป้ายข้อมูล. |
| [getShowLegendKey()](#getShowLegendKey--) | แสดงพฤติกรรมการแสดงคีย์ legend ของป้ายข้อมูลในแผนภูมิที่กำหนด. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | แสดงพฤติกรรมการแสดงคีย์ legend ของป้ายข้อมูลในแผนภูมิที่กำหนด. |
| [getShowValue()](#getShowValue--) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่กำหนด. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | แสดงพฤติกรรมการแสดงค่าร้อยละของป่ายข้อมูลในแผนภูมิที่กำหนด. |
| [getShowCategoryName()](#getShowCategoryName--) | แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิที่กำหนด. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิที่กำหนด. |
| [getShowSeriesName()](#getShowSeriesName--) | คืนค่า หรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | คืนค่า หรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [getShowPercentage()](#getShowPercentage--) | แสดงพฤติกรรมการแสดงค่าร้อยละของป่ายข้อมูลในแผนภูมิที่กำหนด. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | แสดงพฤติกรรมการแสดงค่าร้อยละของป่ายข้อมูลในแผนภูมิที่กำหนด. |
| [getShowBubbleSize()](#getShowBubbleSize--) | แสดงพฤติกรรมการแสดงค่า ขนาดฟองของป้ายข้อมูลในแผนภูมิที่กำหนด. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | แสดงพฤติกรรมการแสดงค่า ขนาดฟองของป่ายข้อมูลในแผนภูมิที่กำหนด. |
| [getShowLeaderLines()](#getShowLeaderLines--) | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่กำหนด. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | แสดงพฤติกรรมการแสดงเส้นนำของป่ายข้อมูลในแผนภูมิที่กำหนด. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | แสดงพฤติกรรมการแสดงค่าของเซลล์ในป้ายข้อมูลของแผนภูมิที่กำหนด. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | แสดงพฤติกรรมการแสดงค่าของเซลล์ในป่ายข้อมูลของแผนภูมิที่กำหนด. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะแสดงเป็นการอ้างอิงข้อมูลหรือเป็นป้ายข้อมูล. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะแสดงเป็นการอ้างอิงข้อมูลหรือเป็นป้ายข้อมูล. |
| [getSeparator()](#getSeparator--) | ตั้งค่า หรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | ตั้งค่า หรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป่ายข้อมูลบนแผนภูมิ. |
| [getTextFormat()](#getTextFormat--) | คืนรูปแบบข้อความของแผนภูมิ. |
| [getChart()](#getChart--) | คืนค่าแผนภูมิ. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection หากตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ IsNumberFormatLinkedToSource ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" ทำให้ DataLabels.get_Item(i).isNumberFormatLinkedToSource() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection หากตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ IsNumberFormatLinkedToSource ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" ทำให้ DataLabels.get_Item(i).isNumberFormatLinkedToSource() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. อ่าน/เขียน String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ NumberFormat สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection เมื่อกำหนดค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ NumberFormat ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" ทำให้ DataLabels.get_Item(i).getNumberFormat() มีค่าเท่ากับ val).

**คืนค่า:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. อ่าน/เขียน String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ NumberFormat สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection เมื่อกำหนดค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ NumberFormat ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" ทำให้ DataLabels.get_Item(i).getNumberFormat() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

แสดงรูปแบบของป่ายข้อมูล. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะเป็นรูปแบบปริยายสำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection.

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

แสดงตำแหน่งของป่ายข้อมูล. อ่าน/เขียน [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ Position สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection แสดงตำแหน่งสำหรับวัตถุ DataLabel ตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ Position ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setPosition(val);" ทำให้ DataLabels.get_Item(i).getPosition() มีค่าเท่ากับ val).

**คืนค่า:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

แสดงตำแหน่งของป่ายข้อมูล. อ่าน/เขียน [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ Position สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection แสดงตำแหน่งสำหรับวัตถุ DataLabel ตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ Position ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setPosition(val);" ทำให้ DataLabels.get_Item(i).getPosition() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

แสดงพฤติกรรมการแสดงคีย์ legend ของป่ายข้อมูลในแผนภูมิที่กำหนด. true หากคีย์ legend ของป่ายข้อมูลมองเห็นได้. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowLegendKey สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ ShowLegendKey ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" ทำให้ DataLabels.get_Item(i).getShowLegendKey() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

แสดงพฤติกรรมการแสดงคีย์ legend ของป่ายข้อมูลในแผนภูมิที่กำหนด. true หากคีย์ legend ของป่ายข้อมูลมองเห็นได้. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowLegendKey สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ ShowLegendKey ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" ทำให้ DataLabels.get_Item(i).getShowLegendKey() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป่ายข้อมูลในแผนภูมิที่กำหนด. true จะแสดงค่าร้อยละ. false จะซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowValue สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ ShowValue ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" ทำให้ DataLabels.get_Item(i).getShowValue() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป่ายข้อมูลในแผนภูมิที่กำหนด. true จะแสดงค่าร้อยละ. false จะซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowValue สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ ShowValue ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" ทำให้ DataLabels.get_Item(i).getShowValue() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป่ายข้อมูลในแผนภูมิที่กำหนด. true จะแสดงชื่อหมวดหมู่สำหรับป่ายข้อมูลบนแผนภูมิ. false จะซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจ็กต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป่ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ ShowCategoryName สำหรับป่ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection ตั้งค่าคุณสมบัตินี้ด้วยค่าใด ๆ ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ ShowCategoryName ของป่ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ทำให้ DataLabels.get_Item(i).getShowCategoryName() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป่ายข้อมูลในแผนภูมิที่กำหนด. true จะแสดงชื่อหมวดหมู่สำหรับป่ายข้อมูลบนแผนภูมิ. false จะซ่อน. อ่าน/เขียน boolean.

--------------------
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get\_Item(i).getShowCategoryName() is equal to val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

คืนหรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อชุดข้อมูลสำหรับป้ายข้อมูลบนแผนภูมิ. True เพื่อแสดงชื่อชุดข้อมูล. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get\_Item(i).getShowSeriesName() is equal to val).

**ค่าที่ส่งกลับ:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

คืนหรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อชุดข้อมูลสำหรับป้ายข้อมูลบนแผนภูมิ. True เพื่อแสดงชื่อชุดข้อมูล. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get\_Item(i).getShowSeriesName() is equal to val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True จะแสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get\_Item(i).getShowPercentage() is equal to val).

**ค่าที่ส่งกลับ:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True จะแสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get\_Item(i).getShowPercentage() is equal to val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. True จะแสดงค่าขนาดฟอง. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get\_Item(i).getShowBubbleSize() is equal to val).

**ค่าที่ส่งกลับ:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. True จะแสดงค่าขนาดฟอง. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get\_Item(i).getShowBubbleSize() is equal to val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. True จะแสดงเส้นนำ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get\_Item(i).getShowLeaderLines() is equal to val).

**ค่าที่ส่งกลับ:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. True จะแสดงเส้นนำ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get\_Item(i).getShowLeaderLines() is equal to val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

แสดงพฤติกรรมการแสดงค่าจากเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ. True จะแสดงค่าจากเซลล์. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get\_Item(i).getShowLabelValueFromCell() is equal to val).

**ค่าที่ส่งกลับ:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

แสดงพฤติกรรมการแสดงค่าจากเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ. True จะแสดงค่าจากเซลล์. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get\_Item(i).getShowLabelValueFromCell() is equal to val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นข้อมูลเรียกเอ้าท์หรือเป็นป้ายข้อมูล.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get\_Item(i).getShowLabelAsDataCallout() is equal to val).

**ค่าที่ส่งกลับ:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นข้อมูลเรียกเอ้าท์หรือเป็นป้ายข้อมูล.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get\_Item(i).getShowLabelAsDataCallout() is equal to val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

ตั้งหรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. อ่าน/เขียน String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get\_Item(i).getSeparator() is equal to val).

**ค่าที่ส่งกลับ:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

ตั้งหรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. อ่าน/เขียน String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get\_Item(i).getSeparator() is equal to val).
**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

คืนค่ารูปแบบข้อความของแผนภูมิ. อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**คืนค่า:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนค่าแผนภูมิ. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)