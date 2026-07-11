---
title: ISensitivityLabelCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию меток чувствительности, применённых к документу.
type: docs
url: /ru/com.aspose.slides/isensitivitylabelcollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Представляет коллекцию меток чувствительности, примененных к документу.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает метку чувствительности по индексу. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Добавляет метку чувствительности в конец коллекции. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Добавляет SensitivityLabel в коллекцию. |
| [removeAt(int index)](#removeAt-int-) | Удаляет метку чувствительности по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [getCount()](#getCount--) | Получает количество всех элементов в коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


Возвращает метку чувствительности по индексу. Только для чтения [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Параметры:**
| Параметр | Type | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Добавляет метку чувствительности в конец коллекции.

**Параметры:**
| Параметр | Type | Описание |
| --- | --- | --- |
| id | java.lang.String | Идентификатор метки чувствительности. |
| siteId | java.util.UUID | Идентификатор сайта Azure Active Directory (Azure AD). |
| isEnabled | boolean | Флаг, указывающий, включена ли метка чувствительности. |
| methodType | int | Метод назначения метки чувствительности. |

**Возвращаемое значение:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


Добавляет SensitivityLabel в коллекцию.

**Параметры:**
| Параметр | Type | Описание |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Объект SensitivityLabel, который будет добавлен в конец коллекции. |

**Возвращаемое значение:**
int - Индекс, по которому был добавлен SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет метку чувствительности по указанному индексу.

**Параметры:**
| Параметр | Type | Описание |
| --- | --- | --- |
| index | int | Индекс метки чувствительности, которую следует удалить. |

### clear() {#clear--}
```
public abstract void clear()
```


Удаляет все элементы из коллекции.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Получает количество всех элементов в коллекции. Только для чтения int .

**Возвращаемое значение:**
int