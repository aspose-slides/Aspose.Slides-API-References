---
title: MasterSlideCollection
second_title: Aspose.Slides için Java API Referansı
description: Ana slaytların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/masterslidecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Ana slaytların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan öğe sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Kullanılmayan ana slaytları kaldırır. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Belirtilen bir ana slaydın bir kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Belirtilen bir ana slaydın bir kopyasını koleksiyondaki belirtilen konuma ekler. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyonun içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir Java iterator döndürür. |
### size() {#size--}
```
public final int size()
```


Koleksiyonda gerçekte bulunan öğe sayısını alır. Yalnızca okunabilir int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Yalnızca okunabilir [MasterSlide](../../com.aspose.slides/masterslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Koleksiyondan kaldırılacak ana slayt. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Koleksiyondaki belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi.

--------------------

PptxEditException hatasının atılmasını önlemek için, önce master'ın HasDependingSlides özelliğini kontrol edin. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Kullanılmayan ana slaytları kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ignorePreserveField | boolean | Bu yöntemin, [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) özelliği true olarak ayarlı olsa bile kullanılmayan master'ı kaldırıp kaldırmayacağını belirler. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Belirtilen bir ana slaydın bir kopyasını koleksiyonun sonuna ekler. Bağlı düzen slaytları da kopyalanacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Klonlanacak slayt. |

**Döndürür:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Eklenen slayt.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Belirtilen bir ana slaydın bir kopyasını koleksiyondaki belirtilen konuma ekler. Bağlı düzen slaytları da kopyalanacaktır.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Kaynak sunum dosyasını yüklemek için Presentation sınıfını örnekle
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Kaydırının kopyalanacağı hedef sunum için Presentation sınıfını örnekle
>      Presentation destPres = new Presentation();
>      try {
>          // Kaynak sunumdaki slayt koleksiyonundan ISlide sınıfını örnekle ve
>          // Ana slaytı da ekle
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Hedef sunumun Ana Slaytlarını al
>          IMasterSlideCollection masters = destPres.getMasters();
>          // İstenen ana slaytı kaynak sunumdan ana slayt koleksiyonuna kopyala
>          // Hedef sunumda
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Hedef sunumdaki slayt koleksiyonu
>          ISlideCollection slds = destPres.getSlides();
>          // Kaynak slaytı hedef slayt koleksiyonuna kopyala.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Hedef sunumu diske kaydet
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Klonlanacak slayt. |

**Döndürür:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Eklenen ana slayt.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Yalnızca okunabilir Object.

**Döndürür:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


Koleksiyonun içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


Tüm koleksiyon için bir Java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Tüm koleksiyon için bir java.util.Iterator.