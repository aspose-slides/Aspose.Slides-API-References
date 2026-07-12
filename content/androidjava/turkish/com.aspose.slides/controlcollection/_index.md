---
title: ControlCollection
second_title: Aspose.Slides Android için Java API Referansı
description: ActiveX denetimlerinin bir koleksiyonu.
type: docs
url: /tr/com.aspose.slides/controlcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX denetimlerinin bir koleksiyonu.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki nesnelerin sayısını döndürür. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Koleksiyonda yeni bir denetim oluşturur ve ekler. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Koleksiyondan bir ActiveX denetimini kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen konumda depolanan bir ActiveX denetimini kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm denetimleri kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen konumdaki denetimi döndürür. |
| [iterator()](#iterator--) | Koleksiyon boyunca yineleyen bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm koleksiyonu belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Koleksiyondaki nesnelerin sayısını döndürür. Yalnızca okunabilir int.

**Döndürür:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Koleksiyonda yeni bir denetim oluşturur ve ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| controlType | int | Eklenecek denetimin tipi. |
| x | float | Şeklin çerçevesinin sol tarafı için X koordinatı. |
| y | float | Şeklin çerçevesinin üst tarafı için Y koordinatı. |
| width | float | Şeklin çerçevesinin genişliği. |
| height | float | Şeklin çerçevesinin yüksekliği. |

**Döndürür:**
[IControl](../../com.aspose.slides/icontrol) - Oluşturulan denetim.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Koleksiyondan bir ActiveX denetimini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Kaldırılacak bir denetim. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Koleksiyonda belirtilen konumda depolanan bir ActiveX denetimini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak denetimin indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm denetimleri kaldırır.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Belirtilen konumdaki denetimi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Denetimin indeksi. |

**Döndürür:**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Koleksiyon boyunca yineleyen bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Koleksiyon boyunca yinelemek için kullanılabilen bir IGenericEnumerator.

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

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okunabilir Object.

**Döndürür:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject