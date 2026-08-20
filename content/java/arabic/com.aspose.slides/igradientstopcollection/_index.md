---
title: IGradientStopCollection
second_title: مرجع API ل Aspose.Slides للـ Java
description: يمثل مجموعة من نقاط التدرج.
type: docs
url: /ar/com.aspose.slides/igradientstopcollection/
---
**جميع الواجهات التي تم تنفيذها:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

يمثل مجموعة من نقاط التدرج.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | تُرجِع نقطة التدرج حسب الفهرس. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | ينشئ نقطة التدرج الجديدة ويدرجها في الفهرس المحدد في المجموعة. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | ينشئ نقطة التدرج الجديدة ويدرجها في الفهرس المحدد في المجموعة. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | ينشئ نقطة التدرج الجديدة ويدرجها في الفهرس المحدد في المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل نقطة التدرج في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع نقاط التدرج من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

تُرجِع نقطة التدرج حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| color | java.awt.Color | لون نقطة التدرج الجديدة. |

**الإرجاع:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| presetColor | int | لون نقطة التدرج الجديدة. |

**الإرجاع:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| schemeColor | int | لون نقطة التدرج الجديدة. |

**الإرجاع:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

ينشئ نقطة التدرج الجديدة ويدرجها في الفهرس المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| color | java.awt.Color | لون نقطة التدرج الجديدة. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

ينشئ نقطة التدرج الجديدة ويدرجها في الفهرس المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| presetColor | int | لون نقطة التدرج الجديدة. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

ينشئ نقطة التدرج الجديدة ويدرجها في الفهرس المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدراج نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| schemeColor | int | لون نقطة التدرج الجديدة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل نقطة التدرج في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس نقطة التدرج التي يجب حذفها. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع نقاط التدرج من المجموعة.