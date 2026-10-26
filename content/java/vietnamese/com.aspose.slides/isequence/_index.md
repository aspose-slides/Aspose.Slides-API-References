---
title: ISequence
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn tập hợp các hiệu ứng theo trình tự.
type: docs
url: /vi/com.aspose.slides/isequence/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Biểu diễn chuỗi (tập hợp các hiệu ứng).
## Các phương thức

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Trả về số lượng hiệu ứng trong một chuỗi. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Xóa hiệu ứng đã chỉ định khỏi một tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa một hiệu ứng khỏi một tập hợp. |
| [clear()](#clear--) | Xóa tất cả các hiệu ứng khỏi một tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về một hiệu ứng tại chỉ mục đã chỉ định. |
| [getTriggerShape()](#getTriggerShape--) | Trả về hoặc đặt đối tượng hình cho chuỗi INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Trả về hoặc đặt đối tượng hình cho chuỗi INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Xóa hiệu ứng cho hình đã chỉ định. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Trả về mảng các hiệu ứng cho hình đã chỉ định. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Trả về mảng các hiệu ứng cho đoạn văn đã chỉ định. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Trả về số lượng hiệu ứng cho hình đã chỉ định. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Thêm hiệu ứng mới vào cuối chuỗi. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Thêm hiệu ứng hoạt ảnh mới cho đoạn văn vào cuối chuỗi. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Thêm hiệu ứng hoạt ảnh biểu đồ mới cho danh mục hoặc chuỗi vào cuối chuỗi. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Thêm hiệu ứng hoạt ảnh biểu đồ mới cho các phần tử trong danh mục hoặc chuỗi vào cuối chuỗi. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Trả về số lượng hiệu ứng trong một chuỗi. Chỉ đọc int.

**Trả về:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Xóa hiệu ứng đã chỉ định khỏi một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Hiệu ứng cần xóa. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa một hiệu ứng khỏi một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hiệu ứng cần xóa int |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các hiệu ứng khỏi một tập hợp.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Trả về một hiệu ứng tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử. |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng [IEffect](../../com.aspose.slides/ieffect)

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Trả về hoặc đặt mục tiêu hình cho chuỗi INTERACTIVE. Nếu chuỗi không tương tác thì trả về null. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Trả về hoặc đặt mục tiêu hình cho chuỗi INTERACTIVE. Nếu chuỗi không tương tác thì trả về null. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Xóa hiệu ứng cho hình đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Đối tượng Shape [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Trả về mảng các hiệu ứng cho hình đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Đối tượng Shape [IShape](../../com.aspose.slides/ishape) |

**Trả về:**
com.aspose.slides.IEffect[] - Mảng các hiệu ứng [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Trả về mảng các hiệu ứng cho đoạn văn đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Đối tượng Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |

**Trả về:**
com.aspose.slides.IEffect[] - Mảng các hiệu ứng [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Trả về số lượng hiệu ứng cho hình đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Đối tượng Shape [IShape](../../com.aspose.slides/ishape) |

**Trả về:**
int - Số lượng hiệu ứng int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng mới vào cuối chuỗi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Đối tượng Shape [IShape](../../com.aspose.slides/ishape) để thêm hiệu ứng |
| effectType | int | Kiểu của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các loại phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Kiểu kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng hoạt ảnh mới cho đoạn văn vào cuối chuỗi.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // chọn đoạn văn để thêm hiệu ứng
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // thêm hiệu ứng hoạt ảnh Fly vào đoạn văn đã chọn
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Đối tượng Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Kiểu của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các loại phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Kiểu kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng hoạt ảnh biểu đồ mới cho danh mục hoặc chuỗi vào cuối chuỗi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Đối tượng Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Kiểu của hiệu ứng hoạt ảnh [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Chỉ mục int |
| effectType | int | Kiểu của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các loại phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Kiểu kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Thêm hiệu ứng hoạt ảnh biểu đồ mới cho các phần tử trong danh mục hoặc chuỗi vào cuối chuỗi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Đối tượng Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Kiểu của hiệu ứng hoạt ảnh [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Chỉ mục của chuỗi biểu đồ int |
| categoriesIndex | int | Chỉ mục của danh mục int |
| effectType | int | Kiểu của hiệu ứng hoạt ảnh [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Các loại phụ của hiệu ứng hoạt ảnh [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Kiểu kích hoạt của hiệu ứng [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Trả về:**
[IEffect](../../com.aspose.slides/ieffect) - Đối tượng hiệu ứng mới [IEffect](../../com.aspose.slides/ieffect)