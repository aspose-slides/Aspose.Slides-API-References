---
title: ActiveXControlBinary
second_title: Справочник по API Aspose.Slides для .NET
description: Задает сохраняемость элемента управления ActiveX когда для сохранения используется метод PersistStream PersistStreamInit или PersistStorage.
type: docs
weight: 10
url: /ru/aspose.slides/control/activexcontrolbinary/
---
## Control.ActiveXControlBinary property

Задает сохраняемость элемента управления ActiveX, когда для сохранения используется метод PersistStream, PersistStreamInit или PersistStorage.

```csharp
public byte[] ActiveXControlBinary { get; }
```

### Примеры

В следующем примере показано использование свойства ActiveXControlBinary для изменения свойств ActiveX:

```csharp
[C#]
if (control.Persistence == PersistenceType.PersistPropertyBag)
{
    control.Properties["Value"] = value;
}
else
{
    YourMethodHere(control.ActiveXControlBinary);  //Используйте свой собственный метод управления свойствами ActiveX, хранящимися в его двоичном файле file
}
```

### Смотрите также

* class [Control](../../control)
* пространство имен [Aspose.Slides](../../control)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
