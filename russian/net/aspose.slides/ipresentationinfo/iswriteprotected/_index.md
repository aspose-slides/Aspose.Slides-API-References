---
title: IsWriteProtected
second_title: Справочник по API Aspose.Slides для .NET
description: Получает значение указывающее защищена ли связанная презентация от записи.
type: docs
weight: 30
url: /ru/net/aspose.slides/ipresentationinfo/iswriteprotected/
---
## IPresentationInfo.IsWriteProtected property

Получает значение, указывающее, защищена ли связанная презентация от записи.

```csharp
public NullableBool IsWriteProtected { get; }
```

### Примечания

Если презентация защищен паролем для открытия, значение свойства равно NotDefined. См.[`NullableBool`](../../nullablebool)перечисление.

### Примеры

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsWriteProtected == NullableBool.True)
{
    Console.WriteLine("The presentation '" + presentationFilePath + "' is write protected by a password.");
}
```

### Смотрите также

* enum [NullableBool](../../nullablebool)
* interface [IPresentationInfo](../../ipresentationinfo)
* пространство имен [Aspose.Slides](../../ipresentationinfo)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->