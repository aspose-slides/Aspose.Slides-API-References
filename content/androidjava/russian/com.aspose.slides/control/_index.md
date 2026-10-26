---
title: Control
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет элемент управления ActiveX.
type: docs
url: /ru/com.aspose.slides/control/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Представляет элемент управления ActiveX.
## Методы

| Метод | Описание |
| --- | --- |
| [getPersistence()](#getPersistence--) | Получает метод, используемый для хранения свойств элемента управления ActiveX. |
| [getName()](#getName--) | Получает или задает имя этого элемента управления. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя этого элемента управления. |
| [getClassId()](#getClassId--) | Получает идентификатор класса этого элемента управления. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Получает идентификатор класса этого элемента управления. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Возвращает объект свойств заполнения изображения элемента управления. |
| [getFrame()](#getFrame--) | Возвращает или задает кадр элемента управления. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Возвращает или задает кадр элемента управления. |
| [getProperties()](#getProperties--) | Возвращает коллекцию свойств ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Указывает сохранение элемента управления ActiveX, когда метод сохранения является PersistStream, PersistStreamInit или PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Получает метод, используемый для хранения свойств элемента управления ActiveX. Только для чтения [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Используйте ваш собственный метод для управления свойствами ActiveX, хранящимися в его бинарном файле
>  }
> ```

**Возвращаемое значение:**
int
### getName() {#getName--}
```
public final String getName()
```

Получает или задает имя этого элемента управления. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Получает или задает имя этого элемента управления. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Получает идентификатор класса этого элемента управления. Только для чтения java.util.UUID.

**Возвращаемое значение:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Получает идентификатор класса этого элемента управления. Только для чтения java.util.UUID.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Возвращает объект свойств заполнения изображения элемента управления. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращаемое значение:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Возвращает или задает кадр элемента управления. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Возвращаемое значение:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Возвращает или задает кадр элемента управления. Чтение/запись [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Возвращает коллекцию свойств ActiveX. Только для чтения [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Примечание: Aspose.Slides поддерживает только свойства ActiveX, основанные на XML. Если свойства хранятся в бинарном формате, это свойство вернёт null.

**Возвращаемое значение:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Указывает сохранение элемента управления ActiveX, когда метод сохранения является PersistStream, PersistStreamInit или PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Используйте ваш собственный метод для управления свойствами ActiveX, хранящимися в его бинарном файле
>  }
> ```

**Возвращаемое значение:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает базовый слайд. Только для чтения [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает презентацию. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)