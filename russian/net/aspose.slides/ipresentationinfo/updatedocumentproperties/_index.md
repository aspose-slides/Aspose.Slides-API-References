---
title: UpdateDocumentProperties
second_title: Справочник по API Aspose.Slides для .NET
description: Обновляет свойства привязанной презентации.
type: docs
weight: 80
url: /ru/net/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo.UpdateDocumentProperties method

Обновляет свойства привязанной презентации.

```csharp
public void UpdateDocumentProperties(IDocumentProperties documentProperties)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| documentProperties | IDocumentProperties | Свойства документа[`IDocumentProperties`](../../idocumentproperties) |

### Примеры

В этом примере показано, как вызвать метод`UpdateDocumentProperties`для обновить свойства документа, возвращаемые вызовом метода[`ReadDocumentProperties`](../readdocumentproperties).

```csharp
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
IDocumentProperties props = info.ReadDocumentProperties();
props.Subject = "New subject";
props.LastSavedTime = DateTime.UtcNow;
info.UpdateDocumentProperties(props);
info.WriteBindedPresentation("new_pres.pptx");
```

### Смотрите также

* interface [IDocumentProperties](../../idocumentproperties)
* interface [IPresentationInfo](../../ipresentationinfo)
* пространство имен [Aspose.Slides](../../ipresentationinfo)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->