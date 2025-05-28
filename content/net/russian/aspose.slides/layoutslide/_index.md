--- 
title: LayoutSlide 
second_title: Справочник по API Aspose.Slides для .NET 
description: Представляет макетный слайд.
type: docs 
weight: 7400 
url: /ru/aspose.slides/layoutslide/
--- 

## Класс LayoutSlide 

Представляет макетный слайд. 

```csharp 
public sealed class LayoutSlide : BaseSlide, ILayoutSlide 
``` 

## Свойства 

| Имя | Описание | 
| --- | --- | 
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). | 
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов ActiveX на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). | 
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). | 
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Возвращает истинное значение, если существует хотя бы один слайд, который зависит от этого макетного слайда. Только для чтения Boolean. | 
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Возвращает менеджер заголовков и нижних колонтитулов макетного слайда. Только для чтения [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). | 
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает легкий доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). | 
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Возвращает тип компоновки этого макетного слайда. Только для чтения [`SlideLayoutType`](../slidelayouttype). | 
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Возвращает или задает главный слайд для макета. Чтение/запись [`IMasterSlide`](../imasterslide). | 
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Возвращает или задает имя слайда. Чтение/запись String. | 
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Возвращает менеджер заполнителей макетного слайда. Только для чтения [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). | 
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). | 
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только для чтения [`IShapeCollection`](../ishapecollection). | 
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Чтение/запись Boolean. | 
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает ID слайда. Только для чтения UInt32. | 
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, который содержит информацию о том, как указанный слайд переходит во время слайд-шоу. Только для чтения [`ISlideShowTransition`](../islideshowtransition). | 
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Возвращает менеджер тем переопределения. Только для чтения [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). | 
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). | 

## Методы 

| Имя | Описание | 
| --- | --- | 
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает действующую тему для этого слайда. | 
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда равны, если все фигуры, стили, тексты, анимация и другие параметры и т. д. равны. Сравнение не учитывает значения уникальных идентификаторов, например, SlideId и динамическое содержимое, например, текущее значение даты в заполнителе даты. | 
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. | 
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Возвращает массив со всеми слайдами, которые зависят от этого макетного слайда. | 
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Объединяет фрагменты с одинаковым форматированием во всех абзацах всех приемлемых фигур. | 
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет фрагменты с одинаковым форматированием во всех абзацах во всех приемлемых фигурах. | 
| [Remove](../../aspose.slides/layoutslide/remove)() | Удаляет макет из презентации. | 

### Также смотрите 

* класс [BaseSlide](../baseslide) 
* интерфейс [ILayoutSlide](../ilayoutslide) 
* пространство имен [Aspose.Slides](../../aspose.slides) 
* сборка [Aspose.Slides](../../) 

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->