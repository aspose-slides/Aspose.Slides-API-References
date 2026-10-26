---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides Java API Referansı
description: Efekt davranışı için zamanlama özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ibehaviorpropertycollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Etki davranışı için zamanlama özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Koleksiyona yeni bir özellik ekler. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | List'te belirli bir öğenin indeksini özellik değerine göre belirler. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Belirtilen indeksde koleksiyona yeni bir özellik (belirtilen özellik değeriyle) ekler. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Koleksiyondan belirtilen özelliği kaldırır. |
| [contains(String propertyValue)](#contains-java.lang.String-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Koleksiyona yeni bir özellik ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Eklemek üzere olan özelliğin değeri. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

List'te belirli bir öğenin indeksini özellik değerine göre belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | özelliğin değeri |

**Dönüş Değeri:**
int - Belirtilen değere sahip özelliğin indeksi
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Belirtilen indeksde koleksiyona yeni bir özellik (belirtilen özellik değeriyle) ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni özelliğin ekleneceği indeks. |
| propertyValue | java.lang.String | Eklemek üzere olan özelliğin değeri. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Koleksiyondan belirtilen özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Kaldırılacak özelliğin değeri. |

**Dönüş Değeri:**
boolean - Bir özelliğin başarılı bir şekilde kaldırılması durumunda true boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak özelliğin değeri. |

**Dönüş Değeri:**
boolean - propertyValue [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.