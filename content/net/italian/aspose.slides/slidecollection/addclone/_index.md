---
title: AddClone
second_title: Aspose.Sildes per .NET API Reference
description: Aggiunge una copia di una diapositiva specificata alla fine della collezione.
type: docs
weight: 50
url: /it/aspose.slides/slidecollection/addclone/
---
## AddClone(ISlide) {#addclone}

Aggiunge una copia di una diapositiva specificata alla fine della collezione.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva da clonare. |

### Valore di ritorno

Nuova diapositiva.

### Osservazioni

Quando si clona una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anche. Il registro interno viene utilizzato per tenere traccia dei master clonati automaticamente, al fine di evitare la creazione di più cloni della stessa diapositiva master. Il clonaggio manuale delle diapositive master non sarà né impedito né registrato. Se hai bisogno di più controllo sul processo di clonazione usa [`AddClone`](../addclone) o [`AddClone`](../addclone) per clonare diapositive, [`AddClone`](../../igloballayoutslidecollection/addclone) o [`AddClone`](../../igloballayoutslidecollection/addclone) per clonare layout e [`AddClone`](../../imasterslidecollection/addclone) per clonare master.

### Vedi anche

* interfaccia [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva da clonare. |
| section | ISection | Sezione per una nuova diapositiva. |

### Valore di ritorno

Nuova diapositiva.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException |  |
| [PptxEditException](../../pptxeditexception) |  |

### Esempi

```csharp
[C#]
using (IPresentation presentation = new Presentation())
{
    presentation.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
    presentation.Sections.AddSection("Section 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Section 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Ora la seconda sezione contiene una copia della prima diapositiva.
}
```

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ISection](../../isection)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Aggiunge una copia di una diapositiva specificata alla fine della collezione.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva da clonare. |
| destLayout | ILayoutSlide | Layout della diapositiva per una nuova diapositiva. |

### Valore di ritorno

Nuova diapositiva.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ILayoutSlide](../../ilayoutslide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Aggiunge una copia di una diapositiva di origine specificata alla fine della collezione. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva di origine). Se non esiste un layout appropriato, il layout della diapositiva di origine verrà clonato (se allowCloneMissingLayout è true) oppure verrà sollevata una PptxEditException (se allowCloneMissingLayout è false).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva da clonare. |
| destMaster | IMasterSlide | Master della diapositiva per una nuova diapositiva. |
| allowCloneMissingLayout | Boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva di origine verrà clonato (se allowCloneMissingLayout è true) oppure verrà sollevata una PptxEditException (se allowCloneMissingLayout è false). |

### Valore di ritorno

Nuova diapositiva.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Sollevata se non esiste un layout appropriato nel master specificato e allowCloneMissingLayout è false. |

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IMasterSlide](../../imasterslide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->