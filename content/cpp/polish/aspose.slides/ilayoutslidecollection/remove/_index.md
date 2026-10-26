---
title: Remove()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Usuwa układ z kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) metoda

Usuwa układ z kolekcji.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Układ slajdu do usunięcia z kolekcji. |
## Uwagi

1) Aby uniknąć rzutu wyjątku PptxEditException, sprawdź wcześniej właściwość HasDependingSlides układu. 2) Możesz również użyć metody [ILayoutSlide::Remove](../../ilayoutslide/remove/), aby uprościć kod.
## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [ILayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)