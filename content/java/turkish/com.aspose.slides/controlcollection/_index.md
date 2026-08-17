---
title: ControlCollection
second_title: Aspose.Slides için Java API Referansı
description: ActiveX kontrollerinin bir koleksiyonu.
type: docs
url: /tr/com.aspose.slides/controlcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX kontrollerinin bir koleksiyonu.
## Metotlar

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki nesne sayısını döndürür. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Koleksiyona yeni bir kontrol oluşturur ve ekler. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Koleksiyondan bir ActiveX kontrolünü kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen konumda saklanan bir ActiveX kontrolünü kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm kontrolleri kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen konumdaki bir kontrolü döndürür. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm koleksiyonu belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki nesne sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Koleksiyona yeni bir kontrol oluşturur ve ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| controlType | int | Eklenecek kontrolün türü. |
| x | float | Şeklin çerçevesinin sol kenarı için X koordinatı. |
| y | float | Şeklin çerçevesinin üst kenarı için Y koordinatı. |
| width | float | Şeklin çerçevesinin genişliği. |
| height | float | Şeklin çerçevesinin yüksekliği. |

**Döndürür:**
[IControl](../../com.aspose.slides/icontrol) - Oluşturulan kontrol.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Koleksiyondan bir ActiveX kontrolünü kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Kaldırılacak bir kontrol. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Koleksiyonda belirtilen konumda saklanan bir ActiveX kontrolünü kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak kontrolün indeksi. |
### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm kontrolleri kaldırır.
### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Belirtilen konumdaki bir kontrolü döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kontrolün indeksi. |

**Döndürür:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Koleksiyon üzerinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Koleksiyon üzerinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Tüm koleksiyonu belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi |
| index | int | Hedef dizideki indeks. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject