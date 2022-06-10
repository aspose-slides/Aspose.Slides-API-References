---
title: Hyperlink
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет собой гиперссылку.
type: docs
weight: 4640
url: /ru/net/aspose.slides/hyperlink/
---
## Hyperlink class

Представляет собой гиперссылку.

```csharp
public class Hyperlink : PVIObject, IHyperlink
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Создает экземпляр гиперссылки, которая указывает на определенный слайд. Примечание:созданная гиперссылка должна быть привязана к какому-либо объекту из той же презентации, иначе ссылка будет сохранена как NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Создает экземпляр гиперссылки. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Создает экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Возвращает гиперссылку, завершающую показ. Только чтение[`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Возвращает гиперссылку на первый слайд презентации. Только чтение[`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Возвращает гиперссылку на последний слайд презентации. Только чтение[`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Возвращает гиперссылку на последний просмотренный слайд. Только чтение[`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Возвращает специальную гиперссылку "проигрывать медиафайл". Используется в AudioFrame и VideoFrame. Только чтение[`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Возвращает гиперссылку на следующий слайд. Только чтение[`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Возвращает специальную гиперссылку "ничего не делать". Только чтение[`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Возвращает гиперссылку на предыдущий слайд. Только чтение[`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Возвращает тип действия гиперссылки. Только для чтения[`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения[`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Представляет источник цвета гиперссылки - стили или формат части. Чтение/запись[`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Указывает внешний URL-адрес. Только чтениеString. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Определяет, должна ли гиперссылка подсвечиваться при щелчке. Чтение/записьBoolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Определяет, будет ли цель родительской гиперссылки добавляться в список просматриваемых гиперссылок при ее вызове. Чтение/записьBoolean. |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Определяет, должен ли звук останавливаться при клике по гиперссылке. Чтение/записьBoolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Возвращает фрейм в родительском наборе фреймов HTML для цели родительской гиперссылки, если она существует. Чтение/записьString. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Если гиперссылка нацелена на определенный слайд, возвращается этот слайд. Только для чтения[`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Возвращает строку, которая может отображаться в пользовательском интерфейсе как связанную с родительской гиперссылкой. Чтение/записьString. |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Определяет, равны ли два экземпляра гиперссылки. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Определяет, равны ли два экземпляра гиперссылки. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Служит хэш-функцией для определенного типа, подходящей для использования в алгоритмах хеширования и структурах данных, таких как хэш-таблица. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Проверяет две гиперссылки на равенство. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Проверяет две гиперссылки на неравенство. |

### Смотрите также

* class [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
