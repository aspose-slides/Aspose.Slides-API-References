---
title: IDataLabelFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.
type: docs
url: /th/com.aspose.slides/idatalabelformat/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | อ่าน/เขียน boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | อ่าน/เขียน boolean. |
| [getNumberFormat()](#getNumberFormat--) | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. |
| [getFormat()](#getFormat--) | แสดงรูปแบบของป้ายข้อมูล. |
| [getPosition()](#getPosition--) | แสดงตำแหน่งของป้ายข้อมูล. |
| [setPosition(int value)](#setPosition-int-) | แสดงตำแหน่งของป้ายข้อมูล. |
| [getShowLegendKey()](#getShowLegendKey--) | แสดงพฤติกรรมการแสดงคีย์ตำนานของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | แสดงพฤติกรรมการแสดงคีย์ตำนานของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowValue()](#getShowValue--) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowCategoryName()](#getShowCategoryName--) | แสดงพฤติกรรมการแสดงชื่อประเภทของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | แสดงพฤติกรรมการแสดงชื่อประเภทของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowSeriesName()](#getShowSeriesName--) | คืนค่า หรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | คืนค่า หรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. |
| [getShowPercentage()](#getShowPercentage--) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowBubbleSize()](#getShowBubbleSize--) | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowLeaderLines()](#getShowLeaderLines--) | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นการอธิบายข้อมูลหรือเป็นป้ายข้อมูล. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นการอธิบายข้อมูลหรือเป็นป้ายข้อมูล. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | แสดงพฤติกรรมการแสดงค่าของเซลล์ป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | แสดงพฤติกรรมการแสดงค่าของเซลล์ป้ายข้อมูลในแผนภูมิที่ระบุ. |
| [getSeparator()](#getSeparator--) | ตั้งค่า หรือคืนค่า Variant ที่เป็นตัวคั่นสำหรับป้ายข้อมูลบนแผนภูมิ. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | ตั้งค่า หรือคืนค่า Variant ที่เป็นตัวคั่นสำหรับป้ายข้อมูลบนแผนภูมิ. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" ทำให้ DataLabels.get_Item(i).isNumberFormatLinkedToSource() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ IsNumberFormatLinkedToSource สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" ทำให้ DataLabels.get_Item(i).isNumberFormatLinkedToSource() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. อ่าน/เขียน String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection เมื่อกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่ง ค่านั้นจะถูกกำหนดให้กับคุณสมบัติ NumberFormat ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" ทำให้ DataLabels.get_Item(i).getNumberFormat() มีค่าเท่ากับ val).

**คืนค่า:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. อ่าน/เขียน String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection เมื่อกำหนดค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่ง ค่านั้นจะถูกกำหนดให้กับคุณสมบัติ NumberFormat ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" ทำให้ DataLabels.get_Item(i).getNumberFormat() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

แสดงรูปแบบของป้ายข้อมูล. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะแสดงรูปแบบตั้งต้นสำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection.

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

แสดงตำแหน่งของป้ายข้อมูล. อ่าน/เขียน [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Position สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection แสดงตำแหน่งสำหรับวัตถุ DataLabel การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ Position ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setPosition(val)" ทำให้ DataLabels.get_Item(i).getPosition() มีค่าเท่ากับ val).

**คืนค่า:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

แสดงตำแหน่งของป้ายข้อมูล. อ่าน/เขียน [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Position สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection แสดงตำแหน่งสำหรับวัตถุ DataLabel การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ Position ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setPosition(val)" ทำให้ DataLabels.get_Item(i).getPosition() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

แสดงพฤติกรรมการแสดงคีย์ตำนานของป้ายข้อมูลในแผนภูมิที่ระบุ. True หากคีย์ตำนานของป้ายข้อมูลเป็นที่มองเห็นได้. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLegendKey สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowLegendKey ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" ทำให้ DataLabels.get_Item(i).getShowLegendKey() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

แสดงพฤติกรรมการแสดงคีย์ตำนานของป้ายข้อมูลในแผนภูมิที่ระบุ. True หากคีย์ตำนานของป้ายข้อมูลเป็นที่มองเห็นได้. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLegendKey สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowLegendKey ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" ทำให้ DataLabels.get_Item(i).getShowLegendKey() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowValue สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowValue ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" ทำให้ DataLabels.get_Item(i).getShowValue() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowValue สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowValue ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" ทำให้ DataLabels.get_Item(i).getShowValue() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

แสดงพฤติกรรมการแสดงชื่อประเภทของป้ายข้อมูลในแผนภูมิที่ระบุ. True เพื่อแสดงชื่อประเภทสำหรับป้ายข้อมูลบนแผนภูมิ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowCategoryName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowCategoryName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ทำให้ DataLabels.get_Item(i).getShowCategoryName() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

แสดงพฤติกรรมการแสดงชื่อประเภทของป้ายข้อมูลในแผนภูมิที่ระบุ. True เพื่อแสดงชื่อประเภทสำหรับป้ายข้อมูลบนแผนภูมิ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowCategoryName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowCategoryName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ทำให้ DataLabels.get_Item(i).getShowCategoryName() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

คืนค่า หรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. True เพื่อแสดงชื่อซีรีส์. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowSeriesName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowSeriesName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ทำให้ DataLabels.get_Item(i).getShowSeriesName() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

คืนค่า หรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. True เพื่อแสดงชื่อซีรีส์. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowSeriesName สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowSeriesName ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ทำให้ DataLabels.get_Item(i).getShowSeriesName() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowPercentage สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowPercentage ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ทำให้ DataLabels.get_Item(i).getShowPercentage() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowPercentage สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowPercentage ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ทำให้ DataLabels.get_Item(i).getShowPercentage() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าขนาดฟอง. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowBubbleSize สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowBubbleSize ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ทำให้ DataLabels.get_Item(i).getShowBubbleSize() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าขนาดฟอง. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowBubbleSize สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowBubbleSize ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ทำให้ DataLabels.get_Item(i).getShowBubbleSize() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงเส้นนำ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLeaderLines สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowLeaderLines ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ทำให้ DataLabels.get_Item(i).getShowLeaderLines() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงเส้นนำ. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLeaderLines สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowLeaderLines ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ทำให้ DataLabels.get_Item(i).getShowLeaderLines() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

กำหนดว่าป้ายข้อมูลในแผนภูมิที่ระบุจะถูกแสดงเป็นการอธิบายข้อมูลหรือเป็นป้ายข้อมูล.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowLabelAsDataCallout ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ทำให้ DataLabels.get_Item(i).getShowLabelAsDataCallout() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

กำหนดว่าป้ายข้อมูลในแผนภูมิที่ระบุจะถูกแสดงเป็นการอธิบายข้อมูลหรือเป็นป้ายข้อมูล.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowLabelAsDataCallout ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ทำให้ DataLabels.get_Item(i).getShowLabelAsDataCallout() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

แสดงพฤติกรรมการแสดงค่าของเซลล์ป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าของเซลล์. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelValueFromCell สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowLabelValueFromCell ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ทำให้ DataLabels.get_Item(i).getShowLabelValueFromCell() มีค่าเท่ากับ val).

**คืนค่า:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

แสดงพฤติกรรมการแสดงค่าของเซลล์ป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าของเซลล์. False เพื่อซ่อน. อ่าน/เขียน boolean.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelValueFromCell สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ ShowLabelValueFromCell ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ทำให้ DataLabels.get_Item(i).getShowLabelValueFromCell() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

ตั้งค่า หรือคืนค่า Variant ที่เป็นตัวคั่นสำหรับป้ายข้อมูลบนแผนภูมิ. อ่าน/เขียน String.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Separator สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ Separator ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ทำให้ DataLabels.get_Item(i).getSeparator() มีค่าเท่ากับ val).

**คืนค่า:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

ตั้งค่า หรือคืนค่า Variant ที่เป็นตัวคั่นสำหรับป้ายข้อมูลบนแผนภูมิ. อ่าน/เขียน String.

--------------------

หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Separator สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านี้ให้กับคุณสมบัติ Separator ของป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ทำให้ DataLabels.get_Item(i).getSeparator() มีค่าเท่ากับ val).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |