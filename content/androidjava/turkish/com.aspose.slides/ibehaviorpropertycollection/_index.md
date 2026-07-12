---
title: IBehaviorPropertyCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Efekt davranışı için zamanlama özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ibehaviorpropertycollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Efekt davranışı için zamanlama özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Koleksiyona yeni bir özellik ekler. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Listede özellik değerine göre belirli bir öğenin dizinini belirler. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Belirtilen dizinde koleksiyona yeni bir özellik (belirtilen özellik değeriyle) ekler. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Koleksiyondan belirtilen özelliği kaldırır. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Belirli bir değerin [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde olup olmadığını belirler. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Koleksiyona yeni bir özellik ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Eklenecek özelliğin değeri. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Listede özellik değerine göre belirli bir öğenin dizinini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Özelliğin değeri |

**Dönüş:**
int - Belirtilen değere sahip özelliğin dizini
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Belirtilen dizinde koleksiyona yeni bir özellik (belirtilen özellik değeriyle) ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni özelliğin ekleneceği dizin. |
| propertyValue | java.lang.String | Eklenecek özelliğin değeri. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Koleksiyondan belirtilen özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Kaldırılacak özelliğin değeri. |

**Dönüş:**
boolean - Özellik başarıyla kaldırıldıysa doğru boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak özelliğin değeri. |

**Dönüş:**
boolean - propertyValue [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa doğru; aksi takdirde yanlış.