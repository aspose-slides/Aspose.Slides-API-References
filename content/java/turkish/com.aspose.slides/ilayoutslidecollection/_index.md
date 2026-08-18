---
title: ILayoutSlideCollection
second_title: Aspose.Slides for Java API Referansı
description: Yerleşim slaytlarının bir koleksiyonu için temel sınıfı temsil eder.
type: docs
url: /tr/com.aspose.slides/ilayoutslidecollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Yerleşim slaytlarının bir koleksiyonu için temel sınıfı temsil eder.
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
| type | byte | Bulunacak yerleşim slaytı tipi. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) belirtilen tipte veya bulunamazsa null.
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

1) PptxEditException'ın atılmasını önlemek için önce yerleşimin HasDependingSlides özelliğini kontrol edin. 2) Kodu basitleştirmek için ayrıca [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) yöntemini kullanabilirsiniz.

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Kullanılmayan yerleşim slaytlarını kaldırır (HasDependingSlides özelliği false olan yerleşim slaytları).