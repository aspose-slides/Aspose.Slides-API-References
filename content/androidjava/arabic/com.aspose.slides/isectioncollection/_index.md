---
title: ISectionCollection
second_title: Aspose.Slides للـ Android عبر مرجع API للـ Java
description: يمثل مجموعة من الأقسام.
type: docs
url: /ar/com.aspose.slides/isectioncollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

يمثل مجموعة من الأقسام.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | أضف قسمًا جديدًا يبدأ من شريحة معينة. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | أضف قسمًا فارغًا إلى الموضع المحدد في المجموعة. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | أزل القسم والشرائح الموجودة في القسم. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | أزل القسم. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | ينقل القسم وشريحاته من المجموعة إلى الموضع المحدد. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | أضف قسمًا فارغًا إلى نهاية المجموعة. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | يعيد فهرس القسم المحدد في المجموعة. |
| [clear()](#clear--) | يزيل جميع الأقسام من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ISection](../../com.aspose.slides/isection).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيم المرجعة:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

أضف قسمًا جديدًا يبدأ من شريحة معينة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | الشريحة الأولى في القسم |

**القيم المرجعة:**
[ISection](../../com.aspose.slides/isection) - القسم المضاف.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

أضف قسمًا فارغًا إلى الموضع المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |
| index | int | فهرس القسم الجديد. |

**القيم المرجعة:**
[ISection](../../com.aspose.slides/isection) - القسم المضاف.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

أزل القسم والشرائح الموجودة في القسم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المراد إزالته من المجموعة. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

أزل القسم. الشرائح الموجودة في القسم سيتم دمجها في القسم السابق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المراد إزالته من المجموعة. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

ينقل القسم وشريحاته من المجموعة إلى الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المراد نقله. |
| index | int | الفهرس الهدف. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

أضف قسمًا فارغًا إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |

**القيم المرجعة:**
[ISection](../../com.aspose.slides/isection) - القسم المضاف.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

يعيد فهرس القسم المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم للبحث عنه. |

**القيم المرجعة:**
int - فهرس القسم أو -1 إذا لم يكن القسم من هذه المجموعة.
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع الأقسام من المجموعة.