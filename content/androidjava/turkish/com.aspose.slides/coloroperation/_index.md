---
title: ColorOperation
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Renk dönüşümlerinde kullanılan farklı renk işlemlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/coloroperation/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Renk dönüşümlerinde kullanılan farklı renk işlemlerini temsil eder. Değiştirilemez nesne.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Yeni bir renk dönüşüm işlemi oluşturur. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Yeni bir renk dönüşüm işlemi oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOperationType()](#getOperationType--) | Bir işlemin tipini döndürür veya ayarlar. |
| [getParameter()](#getParameter--) | Bir işlemin parametresini döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki ColorOperation örneğinin eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için bir hash işlevi görevi görür; hashleme algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Yeni bir renk dönüşüm işlemi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| op | int | İşlem türü. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Yeni bir renk dönüşüm işlemi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| op | int | İşlem türü. |
| parameter | float | İşlem parametresi. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Bir işlemin tipini döndürür veya ayarlar. Salt okunur [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Döndürür:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Bir işlemin parametresini döndürür. Salt okunur float.

**Döndürür:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

İki ColorOperation örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Mevcut ColorOperation ile karşılaştırılacak ColorOperation. |

**Döndürür:**
boolean - **true** eğer belirtilen ColorOperation, mevcut ColorOperation ile eşitse; aksi takdirde **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash işlevi olarak hizmet verir; hashleme algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.

**Döndürür:**
int