---
title: Hyperlink
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет гиперссылку.
type: docs
weight: 5120
url: /ru/aspose.slides/hyperlink/
---
## Класс Hyperlink

Представляет гиперссылку.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Создает экземпляр гиперссылки, указывающей на конкретный слайд. Примечание: созданную гиперссылку следует назначить объекту из той же презентации, иначе ссылка будет сохранена как NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Создает экземпляр гиперссылки. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Создает экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Возвращает гиперссылку, завершающую демонстрацию. Только для чтения [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Возвращает гиперссылку на первый слайд презентации. Только для чтения [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Возвращает гиперссылку на последний слайд презентации. Только для чтения [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Возвращает гиперссылку на последний просмотренный слайд. Только для чтения [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Возвращает специальную гиперссылку "play mediafile". Используется в AudioFrame и VideoFrame. Только для чтения [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Возвращает гиперссылку на следующий слайд. Только для чтения [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Возвращает специальную гиперссылку "do nothing". Только для чтения [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Возвращает гиперссылку на предыдущий слайд. Только для чтения [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Возвращает тип действия гиперссылки. Только для чтения [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Представляет источник цвета гиперссылки — либо стили, либо формат части. Чтение/запись [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Указывает внешний URL. Только для чтения String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Представляет гиперссылку, установленную для этой части независимо от реального содержимого части. PowerPoint ведёт себя особым образом для ссылок и соответствующего им текста в части. Это позволяет создать текст для гиперссылки в виде действительного URL, отличного от реального адреса ссылки. В этом случае, при просмотре ссылки в окне редактирования, она будет изменена, чтобы соответствовать текстовой части. Это свойство содержит исходное значение гиперссылки. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Определяет, следует ли выделять гиперссылку при щелчке. Чтение/запись Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. Чтение/запись Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Представляет звук воспроизведения гиперссылки. Чтение/запись [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Определяет, следует ли прекращать звук при щелчке по гиперссылке. Чтение/запись Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Возвращает кадр в родительском наборе HTML-фреймов для цели родительской гиперссылки, если он существует. Чтение/запись String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Если гиперссылка указывает на конкретный слайд, возвращает этот слайд. Только для чтения [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Возвращает строку, которая может быть отображена в пользовательском интерфейсе как связанная с родительской гиперссылкой. Чтение/запись String. |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Определяет, равны ли два экземпляра Hyperlink. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Определяет, равны ли два экземпляра Hyperlink. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Служит в качестве функции хеширования для конкретного типа, подходящей для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Проверяет два гиперссылки на равенство. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Проверяет два гиперссылки на неравенство. |

### См. также

* класс [PVIObject](../pviobject)
* интерфейс [IHyperlink](../ihyperlink)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->