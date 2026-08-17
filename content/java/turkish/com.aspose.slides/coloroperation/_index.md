---
title: ColorOperation
second_title: Aspose.Slides for Java API Referansı
description: Renk dönüşümlerinde kullanılan farklı renk işlemlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/coloroperation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Farklı renk dönüşümlerinde kullanılan renk işlemlerini temsil eder. Değiştirilemez nesne.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Yeni bir renk dönüşüm işlemi oluşturur. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Yeni bir renk dönüşüm işlemi oluşturur. |
## Methods

| Method | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | Bir işlemin türünü döndürür veya ayarlar. |
| [getParameter()](#getParameter--) | Bir işlemin parametresini döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki ColorOperation örneğinin eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash fonksiyonu olarak hizmet eder; hash tabloları gibi veri yapılarına ve hashing algoritmalarına uygundur. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Yeni bir renk dönüşüm işlemi oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | İşlem türü. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Yeni bir renk dönüşüm işlemi oluşturur.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | İşlem türü. |
| parameter | float | İşlem parametresi. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Bir işlemin türünü döndürür veya ayarlar. Salt okunur [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Returns:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Bir işlemin parametresini döndürür. Salt okunur float.

**Returns:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

İki ColorOperation örneğinin eşit olup olmadığını belirler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Mevcut ColorOperation ile karşılaştırılacak ColorOperation. |

**Returns:**
boolean - **true** eğer belirtilen ColorOperation mevcut ColorOperation ile eşitse; aksi takdirde **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash fonksiyonu olarak hizmet eder; hash tabloları gibi veri yapılarına ve hashing algoritmalarına uygundur.

**Returns:**
int