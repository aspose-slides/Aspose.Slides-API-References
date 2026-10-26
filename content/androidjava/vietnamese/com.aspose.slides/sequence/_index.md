---
title: Sequence
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn tập hợp các hiệu ứng theo chuỗi.
type: docs
url: /vi/com.aspose.slides/sequence/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Đại diện cho chuỗi (tập hợp các hiệu ứng).
## Methods

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Trả về số lượng hiệu ứng trong một chuỗi. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Xóa hiệu ứng được chỉ định khỏi một tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa một hiệu ứng khỏi một tập hợp. |
| [clear()](#clear--) | Xóa tất cả các hiệu ứng khỏi một tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về một hiệu ứng tại chỉ mục đã chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator để duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [getTriggerShape()](#getTriggerShape--) | Trả về hoặc đặt đối tượng shape mục tiêu cho chuỗi INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Trả về hoặc đặt đối tượng shape mục tiêu cho chuỗi INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Xóa hiệu ứng cho shape đã chỉ định. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Trả về mảng các hiệu ứng cho shape đã chỉ định. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Trả về mảng các hiệu ứng cho đoạn văn đã chỉ định. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Trả về số lượng hiệu ứng cho shape đã chỉ định. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Thêm hiệu ứng mới vào cuối chuỗi. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Thêm hiệu ứng hoạt ảnh mới cho đoạn văn vào cuối chuỗi. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Thêm hiệu ứng hoạt ảnh biểu đồ mới cho danh mục hoặc chuỗi vào cuối chuỗi. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Thêm hiệu ứng hoạt ảnh biểu đồ mới cho các phần tử trong danh mục hoặc chuỗi vào cuối chuỗi. |

### getCount() {#getCount--}
```
public final int getCount()
```

Trả về số lượng hiệu ứng trong một chuỗi. Chỉ đọc int.

**Trả về:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Xóa hiệu ứng được chỉ định khỏi một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effect to remove. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa một hiệu ứng khỏi một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hiệu ứng cần xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các hiệu ứng khỏi một tập hợp.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Trả về một hiệu ứng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử. |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng [IEffect](../../com.aspose.slides/ieffect).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Trả về một enumerator để duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - An java.util.Iterator for the entire collection.

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Trả về hoặc đặt đối tượng shape mục tiêu cho chuỗi INTERACTIVE. Nếu chuỗi không tương tác thì trả về null. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Trả về hoặc đặt đối tượng shape mục tiêu cho chuỗi INTERACTIVE. Nếu chuỗi không tương tác thì trả về null. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Xóa hiệu ứng cho shape đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Trả về mảng các hiệu ứng cho shape đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Trả về:**
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Trả về mảng các hiệu ứng cho đoạn văn đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Trả về:**
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Trả về số lượng hiệu ứng cho shape đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Trả về:**
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng mới vào cuối chuỗi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Đối tượng Shape [IShape](../../com.aspose.slides/ishape) để thêm hiệu ứng |
| effectType | int | Loại của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các loại phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Loại kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng hoạt ảnh mới cho đoạn văn vào cuối chuỗi.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // chọn đoạn văn để thêm hiệu ứng
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // thêm hiệu ứng Fly cho đoạn văn đã chọn
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Đối tượng Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Loại của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các loại phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Loại kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng hoạt ảnh biểu đồ mới cho danh mục hoặc chuỗi vào cuối chuỗi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Đối tượng Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Loại của hiệu ứng hoạt ảnh [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Chỉ mục int |
| effectType | int | Loại của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các loại phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Loại kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng hoạt ảnh biểu đồ mới cho các phần tử trong danh mục hoặc chuỗi vào cuối chuỗi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Đối tượng Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Loại của hiệu ứng hoạt ảnh [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Chỉ mục của chuỗi biểu đồ int |
| categoriesIndex | int | Chỉ mục của danh mục int |
| effectType | int | Loại của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các loại phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Loại kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)