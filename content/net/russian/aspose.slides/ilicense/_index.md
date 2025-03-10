---
title: ILicense
second_title: Справочник по API Aspose.Slides для .NET
description: Предоставляет методы для лицензирования компонента.
type: docs
weight: 5700
url: /ru/aspose.slides/ilicense/
---
## ILicense interface

Предоставляет методы для лицензирования компонента.

```csharp
public interface ILicense
```

## Методы

| Имя | Описание |
| --- | --- |
| [ResetLicense](../../aspose.slides/ilicense/resetlicense)() | Сбросить лицензию |
| [SetLicense](../../aspose.slides/ilicense/setlicense#setlicense)(Stream) | Лицензирует компонент. |
| [SetLicense](../../aspose.slides/ilicense/setlicense#setlicense_1)(string) | Лицензирует компонент. |

### Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
