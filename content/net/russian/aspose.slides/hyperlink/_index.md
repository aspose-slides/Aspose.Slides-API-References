---
title: Hyperlink
second_title: Aspose.Sildes for .NET API Reference
description: Представляет гиперссылку.
type: docs
weight: 4920
url: /ru/aspose.slides/hyperlink/
---

## Hyperlink class

Представляет гиперссылку.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Constructors

| Name | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Создает экземпляр гиперссылки, который указывает на конкретный слайд. Примечание: созданная гиперссылка должна быть назначена какому-либо объекту из той же презентации, иначе ссылка будет сохранена как NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Создает экземпляр гиперссылки. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Создает экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства. |

## Properties

| Name | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Возвращает гиперссылку, которая завершает показ. Только для чтения [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Возвращает гиперссылку на первый слайд презентации. Только для чтения [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Возвращает гиперссылку на последний слайд презентации. Только для чтения [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Возвращает гиперссылку на последний просмотренный слайд. Только для чтения [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Возвращает специальную гиперссылку "воспроизвести медиафайл". Используется в AudioFrame и VideoFrame. Только для чтения [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Возвращает гиперссылку на следующий слайд. Только для чтения [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Возвращает специальную гиперссылку "ничего не делать". Только для чтения [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Возвращает гиперссылку на предыдущий слайд. Только для чтения [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Возвращает тип действия гиперссылки. Только для чтения [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовой интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Представляет источник цвета гиперссылки - либо стили, либо формат порции. Чтение/запись [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Указывает внешний URL. Только для чтения String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Представляет гиперссылку, которая установлена для этой порции, независимо от фактического содержания порции. PowerPoint ведет себя специфическим образом для ссылок и соответствующего текста в порции. Он позволяет создавать текст для гиперссылки в виде действительного URL, отличного от реального адреса ссылки. В этом случае, когда вы просматриваете ссылку в окне редактирования, она будет изменена, чтобы соответствовать тексту порции. Это свойство представляет оригинальное значение гиперссылки. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Определяет, должна ли гиперссылка подсвечиваться при нажатии. Чтение/запись Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Определяет, должен ли целевой элемент родительской гиперссылки быть добавлен в список просмотренных гиперссылок, когда он вызывается. Чтение/запись Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Представляет воспроизводимый звук гиперссылки. Чтение/запись [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Определяет, должен ли звук быть остановлен при нажатии на гиперссылку. Чтение/запись Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Возвращает фрейм в родительском HTML-фреймовой системе для цели родительской гиперссылки, когда она существует. Чтение/запись String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Если гиперссылка нацелена на конкретный слайд, возвращает этот слайд. Только для чтения [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Возвращает строку, которая может быть отображена в пользовательском интерфейсе, как связанная с родительской гиперссылкой. Чтение/запись String. |

## Methods

| Name | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Определяет, равны ли два экземпляра Hyperlink. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Определяет, равны ли два экземпляра Hyperlink. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Служит хеш-функцией для конкретного типа, подходит для использования в хеширующих алгоритмах и структурах данных, таких как хеш-таблица. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Проверяет два гиперссылки на равенство. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Проверяет два гиперссылки на неравенство. |

### See Also

* class [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->