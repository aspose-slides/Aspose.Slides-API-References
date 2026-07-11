---
title: ICustomXmlPartCollection
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет коллекцию пользовательских XML-частей.
type: docs
url: /ru/com.aspose.slides/icustomxmlpartcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Представляет коллекцию пользовательских XML-частей.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [add(byte[] xmlData)](#add-byte---) | Добавляет новую пользовательскую XML-часть. |
| [add(String xmlString)](#add-java.lang.String-) | Добавляет новую пользовательскую XML-часть. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Добавляет новую пользовательскую XML-часть. |
| [removeAt(int index)](#removeAt-int-) | Удаляет пользовательскую XML-часть по указанному индексу. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Возвращает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно получить. |

**Возвращаемое значение:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Элемент по указанному индексу.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Добавляет новую пользовательскую XML-часть.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlData | byte[] | XML-данные новой части, которую необходимо добавить. |

**Возвращаемое значение:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Создана пользовательская XML-часть.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Добавляет новую пользовательскую XML-часть.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlString | java.lang.String | XML-строка новой части, которую необходимо добавить. |

**Возвращаемое значение:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Создана пользовательская XML-часть.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Добавляет новую пользовательскую XML-часть.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream с XML-данными новой части, которую необходимо добавить. |

**Возвращаемое значение:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Создана пользовательская XML-часть.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет пользовательскую XML-часть по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Удаляет первое вхождение конкретного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Пользовательскую XML-часть для удаления. |

**Возвращаемое значение:**
boolean - true если элемент успешно удалён; иначе false.
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы из коллекции.