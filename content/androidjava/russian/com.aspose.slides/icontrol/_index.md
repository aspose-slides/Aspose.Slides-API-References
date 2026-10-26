---
title: IControl
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет элемент управления ActiveX.
type: docs
url: /ru/com.aspose.slides/icontrol/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Представляет элемент управления ActiveX.
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Возвращает имя этого элемента управления. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает имя этого элемента управления. |
| [getClassId()](#getClassId--) | Получает идентификатор класса этого элемента управления. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Возвращает объект свойств заполнения изображения ControlEx. |
| [getFrame()](#getFrame--) | Возвращает или задает кадр элемента управления. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Возвращает или задает кадр элемента управления. |
| [getProperties()](#getProperties--) | Возвращает коллекцию свойств ActiveX. |
| [getPersistence()](#getPersistence--) | Получает метод, используемый для хранения свойств элемента управления ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Указывает способ сохранения элемента управления ActiveX, когда используемый метод сохранения является PersistStream, PersistStreamInit или PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает имя этого элемента управления. Чтение/запись String.

**Возвращает:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Возвращает имя этого элемента управления. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Получает идентификатор класса этого элемента управления. Только для чтения java.util.UUID.

**Возвращает:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Возвращает объект свойств заполнения изображения ControlEx. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращает:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Возвращает или задает кадр элемента управления. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Возвращает:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Возвращает или задает кадр элемента управления. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Возвращает коллекцию свойств ActiveX. Только для чтения [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Возвращает:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Получает метод, используемый для хранения свойств элемента управления ActiveX. Только для чтения [PersistenceType](../../com.aspose.slides/persistencetype).

**Возвращает:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Указывает способ сохранения элемента управления ActiveX, когда используемый метод сохранения является PersistStream, PersistStreamInit или PersistStorage.

**Возвращает:**
byte[]