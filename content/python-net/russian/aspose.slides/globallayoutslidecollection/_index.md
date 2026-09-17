---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection класс

Представляет коллекцию всех слайдов-макетов в презентации.  
Extends LayoutSlideCollection класс with methods for adding/cloning layout slides in context of uniting of the individual collections of master's layout slides.

**Наследование:**[`GlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/ru/aspose.slides/layoutslidecollection)

Тип GlobalLayoutSlideCollection раскрывает следующие члены:

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Добавляет копию указанного слайда-макета в презентацию. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Добавляет копию указанного слайда-макета в презентацию. |
| [`get_by_type(self, type)`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Возвращает первый слайд-макет указанного типа.<br/>            Тип слайда-макета, который нужно найти.[`LayoutSlide`](/slides/python-net/ru/aspose.slides/layoutslide) с указанным типом или None, если макеты не найдены. |
| [`remove(self, value)`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Удаляет макет из коллекции. |
| [`remove_unused(self)`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection/remove_unused/#) | Удаляет неиспользуемые слайды-макеты (слайды-макеты, у которых HasDependingSlides равно false). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Добавляет новый слайд-макет в презентацию. |


### См. также
* класс [`GlobalLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/globallayoutslidecollection)
* класс [`LayoutSlideCollection`](/slides/python-net/ru/aspose.slides/layoutslidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)