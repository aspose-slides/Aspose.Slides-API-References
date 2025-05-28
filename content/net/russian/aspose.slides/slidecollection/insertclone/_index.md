---
title: InsertClone
second_title: Aspose.Slides для .NET API Справочник
description: Вставляет копию указанного слайда в заданную позицию коллекции.
type: docs
weight: 120
url: /ru/aspose.slides/slidecollection/insertclone/
---

## InsertClone(int, ISlide) {#insertclone}

Вставляет копию указанного слайда в заданную позицию коллекции.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс нового слайда. |
| sourceSlide | ISlide | Слайд для клонирования. |

### Значение Возврата

Вставленный слайд.

### Примечания

При клонировании слайда между различными презентациями может быть клонирован и мастер слайда. Внутренний реестр используется для автоматического отслеживания клонированных мастеров, чтобы предотвратить создание нескольких клонов одного и того же мастер-слайда. Ручное клонирование мастер-слайдов не будет запрещено и не будет зарегистрировано. Если вам нужно больше контроля над процессом клонирования, используйте [`InsertClone`](../insertclone) или [`InsertClone`](../insertclone) для клонирования слайдов и [`AddClone`](../../imasterslidecollection/addclone) для клонирования мастеров.

### Примеры

Следующий пример показывает, как клонировать на другую позицию внутри презентации.

```csharp
[C#]
// Создание экземпляра класса Presentation, который представляет файл презентации
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Клонирование нужного слайда в конец коллекции слайдов в одной и той же презентации
    ISlideCollection slds = pres.Slides;
    // Клонирование нужного слайда в указанном индексе в одной и той же презентации
    slds.InsertClone(2, pres.Slides[1]);
    // Запись измененной презентации на диск
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

Следующий пример показывает, как клонировать на другую позицию внутри презентации.

```csharp
[C#]
// Создание экземпляра класса Presentation для загрузки исходного файла презентации
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Создание экземпляра класса Presentation для целевого PPTX (где слайд будет клонирован)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Запись целевой презентации на диск
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### См. также

* интерфейс [ISlide](../../islide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Вставляет копию указанного слайда в заданную позицию коллекции.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс нового слайда. |
| sourceSlide | ISlide | Слайд для клонирования. |
| destLayout | ILayoutSlide | Макет слайда для нового слайда. |

### Значение Возврата

Вставленный слайд.

### См. также

* интерфейс [ISlide](../../islide)
* интерфейс [ILayoutSlide](../../ilayoutslide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Вставляет копию указанного исходного слайда в заданную позицию коллекции. Подходящий макет будет автоматически выбран из указанного мастера (подходящий макет — это макет с тем же типом или именем, что и макет исходного слайда). Если подходящего макета нет, то макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс нового слайда. |
| sourceSlide | ISlide | Слайд для клонирования. |
| destMaster | IMasterSlide | Мастер слайда для нового слайда. |
| allowCloneMissingLayout | Boolean | Если в указанном мастере нет подходящего макета, то макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |

### Значение Возврата

Вставленный слайд.

### Исключения

| исключение | условие |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Выбрасывается, если в указанном мастере нет подходящего макета и allowCloneMissingLayout равно false. |

### См. также

* интерфейс [ISlide](../../islide)
* интерфейс [IMasterSlide](../../imasterslide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
