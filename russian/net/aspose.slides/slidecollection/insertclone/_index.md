---
title: InsertClone
second_title: Справочник по API Aspose.Slides для .NET
description: Вставляет копию указанного слайда в указанную позицию коллекции.
type: docs
weight: 120
url: /ru/net/aspose.slides/slidecollection/insertclone/
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

Вставлен слайд.

### Примечания

При клонировании слайда между разными презентациями мастер слайда также может быть клонирован. Внутренний реестр используется для отслеживания автоматически клонируемых мастер-слайдов, чтобы предотвратить создание нескольких клонов одного и того же мастер-слайда. Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано. Если вам нужно больше контроля над процессом клонирования, используйте [`InsertClone`](../insertclone)или [`InsertClone`](../insertclone)для клонирования слайдов и [`AddClone`](../../imasterslidecollection/addclone)для клонирования мастеров.

### Смотрите также

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
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

Вставлен слайд.

### Смотрите также

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* class [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Вставляет копию указанного исходного слайда в указанную позицию коллекции. Соответствующий макет будет выбран автоматически из указанного мастера (подходящим макетом является макет с тем же типом или именем, что и макета исходного слайда). ). Если подходящего макета нет, то макет исходного слайда будет клонирован (если значение allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout является ложным).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс нового слайда. |
| sourceSlide | ISlide | Слайд для клонирования. |
| destMaster | IMasterSlide | Мастер-слайд для нового слайда. |
| allowCloneMissingLayout | Boolean | Если в указанном мастере нет подходящего макета, то будет клонирован макет исходного слайда (если значение allowCloneMissingLayout равно true) или PptxEditException будет сгенерировано (если значение allowCloneMissingLayout равно false). |

### Возвращаемое значение

Вставлен слайд.

### Исключения

| исключение | условие |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Вызывается, если в указанном мастере нет подходящего макета и allowCloneMissingLayout имеет значение false. |

### Смотрите также

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* class [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->