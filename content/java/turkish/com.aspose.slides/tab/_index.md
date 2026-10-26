---
title: Tab
second_title: Aspose.Slides for Java API Referansı
description: Metin için bir sekme temsil eder.
type: docs
url: /tr/com.aspose.slides/tab/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Metin için bir sekme temsil eder.

## Constructors

| Constructor | Description |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Yeni Tab oluşturur |

## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Sekmenin konumunu döndürür veya ayarlar. |
| [setPosition(double value)](#setPosition-double-) | Sekmenin konumunu döndürür veya ayarlar. |
| [getAlignment()](#getAlignment--) | Sekmenin hizalama stilini döndürür veya ayarlar. |
| [setAlignment(int value)](#setAlignment-int-) | Sekmenin hizalama stilini döndürür veya ayarlar. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Geçerli örneği aynı tipteki başka bir nesneyle karşılaştırır. |

### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Yeni Tab oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | double | Sekme konumu. |
| align | int | Hizalama. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca-okunur long.

**Döndürür:**  
long

### getPosition() {#getPosition--}
```
public final double getPosition()
```

Sekmenin konumunu döndürür veya ayarlar. Bu özelliğe değer atamak, sekmenin koleksiyondaki indeksini değiştirebilir ve Enumerator'ı geçersiz kılabilir. Okunur/yazılabilir double.

**Döndürür:**  
double

### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Sekmenin konumunu döndürür veya ayarlar. Bu özelliğe değer atamak, sekmenin koleksiyondaki indeksini değiştirebilir ve Enumerator'ı geçersiz kılabilir. Okunur/yazılabilir double.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Sekmenin hizalama stilini döndürür veya ayarlar. Okunur/yazılabilir [TabAlignment](../../com.aspose.slides/tabalignment).

**Döndürür:**  
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Sekmenin hizalama stilini döndürür veya ayarlar. Okunur/yazılabilir [TabAlignment](../../com.aspose.slides/tabalignment).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Geçerli örneği aynı tipteki başka bir nesneyle karşılaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak bir nesne. |

**Döndürür:**
int - Karşılaştırılan nesnelerin göreceli sırasını belirten 32-bit tamsayı. Döndürüm değeri şu anlamlara gelir:

 * < 0 - Bu örnek objeden küçüktür.
 * = 0 - Bu örnek objeye eşittir.
 * > 0 - Bu örnek objeden büyüktür.