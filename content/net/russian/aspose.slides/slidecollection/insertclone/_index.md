---
title: InsertClone
second_title: Aspose.Sildes для .NET API Справочник
description: Вставляет копию указанного слайда в указанную позицию коллекции.
type: docs
weight: 120
url: /ru/aspose.slides/slidecollection/insertclone/
---

## InsertClone(int, ISlide) {#insertclone}

Вставляет копию указанного слайда в указанную позицию коллекции.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс нового слайда. |
| sourceSlide | ISlide | Слайд для клонирования. |

### Возвращаемое значение

Вставленный слайд.

### Замечания

При клонировании слайда между разными презентациями может быть также клонирован мастер слайда. Внутренний реестр используется для автоматического отслеживания клонированных мастеров, чтобы предотвратить создание нескольких клонов одного и того же мастера слайда. Ручное клонирование мастеров слайдов не будет ни предотвращено, ни зарегистрировано. Если вам нужен больший контроль над процессом клонирования, используйте [`InsertClone`](../insertclone) или [`InsertClone`](../insertclone) для клонирования слайдов и [`AddClone`](../../imasterslidecollection/addclone) для клонирования мастеров.

### Примеры

Следующий пример показывает, как клонировать слайд на другую позицию в рамках презентации.

```csharp
[C#]
// Создайте экземпляр класса Presentation, представляющего файл презентации
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Клонируйте желаемый слайд в конец коллекции слайдов в той же презентации
    ISlideCollection slds = pres.Slides;
    // Клонируйте желаемый слайд в указанном индексе в той же презентации
    slds.InsertClone(2, pres.Slides[1]);
    // Запишите измененную презентацию на диск
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

Следующий пример показывает, как клонировать слайд на другую позицию в рамках презентации.

```csharp
[C#]
// Создайте экземпляр класса Presentation для загрузки исходного файла презентации
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Создайте экземпляр класса Presentation для целевого PPTX (куда будет клонирован слайд)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Запишите целевую презентацию на диск
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### См. также

* интерфейс [ISlide](../../islide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Вставляет копию указанного слайда в указанную позицию коллекции.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс нового слайда. |
| sourceSlide | ISlide | Слайд для клонирования. |
| destLayout | ILayoutSlide | Макет слайда для нового слайда. |

### Возвращаемое значение

Вставленный слайд.

### См. также

* интерфейс [ISlide](../../islide)
* интерфейс [ILayoutSlide](../../ilayoutslide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Вставляет копию указанного исходного слайда в указанную позицию коллекции. Соответствующий макет будет автоматически выбран из указанного мастера (соответствующий макет — это макет с тем же типом или именем, что и у макета исходного слайда). Если соответствующего макета нет, то макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс нового слайда. |
| sourceSlide | ISlide | Слайд для клонирования. |
| destMaster | IMasterSlide | Мастер слайда для нового слайда. |
| allowCloneMissingLayout | Boolean | Если в указанном мастере нет соответствующего макета, то макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |

### Возвращаемое значение

Вставленный слайд.

### Исключения

| исключение | условие |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Выбрасывается, если в указанном мастере нет соответствующего макета, и allowCloneMissingLayout равно false. |

### См. также

* интерфейс [ISlide](../../islide)
* интерфейс [IMasterSlide](../../imasterslide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->