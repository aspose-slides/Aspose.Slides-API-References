---
title: DigitalSignatureCollection
second_title: Aspose.Slides for Java API Referansı
description: Belgeye eklenmiş dijital imzaların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/digitalsignaturecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

Belgeye eklenmiş dijital imzaların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İmza, indeks ile döndürülür. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | İmza, koleksiyonun sonuna eklenir. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki imza kaldırılır. |
| [clear()](#clear--) | Koleksiyondaki tüm imzalar kaldırılır. |
| [iterator()](#iterator--) | Koleksiyonun içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [size()](#size--) | Koleksiyondaki eleman sayısını döndürür. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm elemanları belirtilen diziye kopyalar. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

İmza, indeks ile döndürülür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

İmza, koleksiyonun sonuna eklenir.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Eklenecek imza. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen indeksdeki imza kaldırılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken imzanın indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm imzalar kaldırılır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

Koleksiyonun içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Tüm koleksiyon için bir java.util.Iterator.
### size() {#size--}
```
public final int size()
```

Koleksiyondaki eleman sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm elemanları belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |