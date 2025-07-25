---
title: Equals
second_title: Aspose.Sildes для .NET API Reference
description: Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайдов и статического содержимого. Два слайда равны, если все формы, стили, текст, анимация и другие настройки и т. д. равны. Сравнение не учитывает значения уникальных идентификаторов, например, SlideId и динамическое содержимое, например, текущее значение даты в заполнителе даты.
type: docs
weight: 130
url: /ru/aspose.slides/baseslide/equals/
---

## BaseSlide.Equals method

Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда равны, если все формы, стили, текст, анимация и другие настройки и т. д. равны. Сравнение не учитывает значения уникальных идентификаторов, например, SlideId и динамическое содержимое, например, текущее значение даты в заполнителе даты.

```csharp
public bool Equals(IBaseSlide slide)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | IBaseSlide | IBaseSlide для сравнения с текущим IBaseSlide. |

### Возвращаемое значение

**true**, если указанный IBaseSlide равен текущему IBaseSlide; иначе **false**.

### Примеры

Следующий пример демонстрирует, как сравнить два слайда.

```csharp
[C#]
using (Presentation presentation1 = new Presentation("AccessSlides.pptx"))
{
	using (Presentation presentation2 = new Presentation("HelloWorld.pptx"))
	{
		for (int i = 0; i < presentation1.Masters.Count; i++)
		{
			for (int j = 0; j < presentation2.Masters.Count; j++)
			{
				if (presentation1.Masters[i].Equals(presentation2.Masters[j]))
					Console.WriteLine(string.Format("SomePresentation1 MasterSlide#{0} равен SomePresentation2 MasterSlide#{1}", i, j));
			}
		}
	}
}
```

### Смотрите также

* интерфейс [IBaseSlide](../../ibaseslide)
* класс [BaseSlide](../../baseslide)
* пространство имен [Aspose.Slides](../../baseslide)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->