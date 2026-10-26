---
title: ILayoutSlideCollection
second_title: Android için Java API Referansı üzerinden Aspose.Slides
description: Yerleşim slaytları koleksiyonu için temel bir sınıfı temsil eder.
type: docs
url: /tr/com.aspose.slides/ilayoutslidecollection/
---
**Tüm Gerçekleştirilen Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Yerleşim slaytları koleksiyonu için temel bir sınıfı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Dizine göre yerleşim slaytını döndürür. |
| [getByType(byte type)](#getByType-byte-) | Belirtilen tipteki ilk yerleşim slaytını döndürür. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Koleksiyondan bir yerleşimi kaldırır. |
| [removeUnused()](#removeUnused--) | Kullanılmayan yerleşim slaytlarını kaldırır (HasDependingSlides özelliği false olan yerleşim slaytları). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Dizine göre yerleşim slaytını döndürür. Salt okunur [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Belirtilen tipteki ilk yerleşim slaytını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | byte | Bulunacak yerleşim slaytının tipi. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) belirtilen tipte veya yerleşim bulunamazsa null.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Koleksiyondan bir yerleşimi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Koleksiyondan kaldırılacak yerleşim slaytı.

--------------------

1) PptxEditException hatasının atılmasını önlemek için önce yerleşimin HasDependingSlides özelliğini kontrol edin. 2) Kodu basitleştirmek için ayrıca [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metodunu da kullanabilirsiniz. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Kullanılmayan yerleşim slaytlarını kaldırır (HasDependingSlides özelliği false olan yerleşim slaytları).