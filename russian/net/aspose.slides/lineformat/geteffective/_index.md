---
title: GetEffective
second_title: Справочник по API Aspose.Slides для .NET
description: Получает действующие данные форматирования строки с примененным наследованием.
type: docs
weight: 190
url: /ru/net/aspose.slides/lineformat/geteffective/
---
## LineFormat.GetEffective method

Получает действующие данные форматирования строки с примененным наследованием.

```csharp
public ILineFormatEffectiveData GetEffective()
```

### Возвращаемое значение

AILLineFormatEffectiveData.

### Примеры

Этот пример демонстрирует получение эффективных свойств формата линии формы.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
	ILineFormatEffectiveData effectiveLineFormat = pres.Slides[0].Shapes[0].LineFormat.GetEffective();

	Console.WriteLine("Style: " + effectiveLineFormat.Style);
	Console.WriteLine("Width: " + effectiveLineFormat.Width);
	Console.WriteLine("Fill type: " + effectiveLineFormat.FillFormat.FillType);
}
```

### Смотрите также

* interface [ILineFormatEffectiveData](../../ilineformateffectivedata)
* class [LineFormat](../../lineformat)
* пространство имен [Aspose.Slides](../../lineformat)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->