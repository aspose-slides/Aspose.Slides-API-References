---
title: SensitivityLabelCollection
second_title: Aspose.Slides для Java – справочник API
description: Представляет коллекцию меток конфиденциальности, применённых к документу.
type: docs
url: /ru/com.aspose.slides/sensitivitylabelcollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Представляет коллекцию меток конфиденциальности, применённых к документу.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает метку конфиденциальности по индексу. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Добавляет метку конфиденциальности в конец коллекции. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Добавляет объект SensitivityLabel в коллекцию. |
| [removeAt(int index)](#removeAt-int-) | Удаляет метку конфиденциальности по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [getCount()](#getCount--) | Возвращает количество элементов в коллекции. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Копирует все элементы из коллекции в указанный массив. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Возвращает метку конфиденциальности по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возврат:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Добавляет метку конфиденциальности в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | java.lang.String | Идентификатор метки конфиденциальности. |
| siteId | java.util.UUID | Идентификатор сайта Azure Active Directory (Azure AD). |
| isEnabled | boolean | Флаг, указывающий, включена ли метка конфиденциальности. |
| methodType | int | Метод назначения метки конфиденциальности. |

**Возврат:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Добавляет объект SensitivityLabel в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Объект SensitivityLabel, который будет добавлен в конец коллекции. |

**Возврат:**
int - Индекс, по которому была добавлена SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет метку конфиденциальности по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс метки конфиденциальности, которую нужно удалить. |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все элементы из коллекции.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Возвращает перечислитель, который перебирает элементы коллекции.

**Возврат:**
com.aspose.ms System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Объект  System.Collections.Generic.IEnumerator1 , который можно использовать для перебора элементов коллекции.
### getCount() {#getCount--}
```
public final int getCount()
```


Возвращает количество элементов в коллекции. Только для чтения  int .

**Возврат:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |