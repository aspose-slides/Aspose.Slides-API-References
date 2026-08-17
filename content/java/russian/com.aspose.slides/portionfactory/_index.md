---
title: PortionFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создавать тестовые части
type: docs
url: /ru/com.aspose.slides/portionfactory/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Позволяет создавать тестовые части

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createPortion()](#createPortion--) | Создает пустую текстовую часть. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Создает текстовую часть из указанной строки. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Создает часть с использованием данных заданной части. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

Создает пустую текстовую часть.

**Возврат:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

Создает текстовую часть из указанной строки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | Строка. |

**Возврат:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

Создает часть с использованием данных заданной части.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Часть для использования. |

**Возврат:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.