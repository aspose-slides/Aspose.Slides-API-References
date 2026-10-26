---
title: ISectionCollection
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل مجموعة من الأقسام.
type: docs
url: /ar/com.aspose.slides/isectioncollection/
---
**جميع الواجهات المُنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

يمثل مجموعة من الأقسام.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | إضافة قسم جديد يبدأ من شريحة محددة. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | إضافة قسم فارغ إلى الموضع المحدد في المجموعة. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | إزالة القسم والشرائح المحتواة في القسم. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | إزالة القسم. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | نقل القسم وشرائحه من المجموعة إلى الموضع المحدد. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | إضافة قسم فارغ إلى نهاية المجموعة. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | إرجاع فهرس القسم المحدد في المجموعة. |
| [clear()](#clear--) | إزالة جميع الأقسام من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```


يحصل على العنصر في الفهرس المحدد. قراءة فقط [ISection](../../com.aspose.slides/isection).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


إضافة قسم جديد يبدأ من شريحة محددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | أول شريحة في القسم |

**القيمة المرجعة:**
[ISection](../../com.aspose.slides/isection) - تم إضافة القسم.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


إضافة قسم فارغ إلى الموضع المحدد في المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |
| index | int | فهرس القسم الجديد. |

**القيمة المرجعة:**
[ISection](../../com.aspose.slides/isection) - تم إضافة القسم.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


إزالة القسم والشرائح المحتواة في القسم.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المراد إزالته من المجموعة. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


إزالة القسم. الشرائح المحتواة في القسم سيتم دمجها مع القسم السابق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم المراد إزالته من المجموعة. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


نقل القسم وشرائحه من المجموعة إلى الموضع المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم للنقل. |
| index | int | الفهرس الهدف. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


إضافة قسم فارغ إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم القسم |

**القيمة المرجعة:**
[ISection](../../com.aspose.slides/isection) - تم إضافة القسم.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


إرجاع فهرس القسم المحدد في المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | القسم للبحث عنه. |

**القيمة المرجعة:**
int - فهرس القسم أو -1 إذا لم يكن القسم من هذه المجموعة.
### clear() {#clear--}
```
public abstract void clear()
```


إزالة جميع الأقسام من المجموعة.