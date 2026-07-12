---
title: IControlCollection
second_title: Aspose.Slides for Android Java API Referansı aracılığıyla
description: ActiveX denetimlerinin bir koleksiyonu.
type: docs
url: /tr/com.aspose.slides/icontrolcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

ActiveX denetimlerinin bir koleksiyonu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Koleksiyondan bir ActiveX denetimini kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen konumda saklanan bir ActiveX denetimini kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm denetimleri kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen konumdaki bir denetimi döndürür. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Koleksiyona yeni bir denetim oluşturur ve ekler. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Koleksiyondan bir ActiveX denetimini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Kaldırılacak bir denetim. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyonda belirtilen konumda saklanan bir ActiveX denetimini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak bir denetimin indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm denetimleri kaldırır.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Belirtilen konumdaki bir denetimi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Bir denetimin indeksi. |

**Dönen Değer:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Koleksiyona yeni bir denetim oluşturur ve ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| controlType | int | Eklenecek denetimin türü. |
| x | float | Şekil çerçevesinin sol tarafı için X koordinatı. |
| y | float | Şekil çerçevesinin üst tarafı için Y koordinatı. |
| width | float | Şekil çerçevesinin genişliği. |
| height | float | Şekil çerçevesinin yüksekliği. |

**Dönen Değer:**
[IControl](../../com.aspose.slides/icontrol) - Oluşturulan denetim [IControl](../../com.aspose.slides/icontrol).