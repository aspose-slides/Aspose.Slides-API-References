---
title: InsertClone
second_title: Riferimento API Aspose.Slides per .NET
description: Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.
type: docs
weight: 120
url: /it/aspose.slides/slidecollection/insertclone/
---
## InsertClone(int, ISlide) {#insertclone}

Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Indice della nuova diapositiva. |
| sourceSlide | ISlide | Diapositiva da clonare. |

### Valore di ritorno

Diapositiva inserita.

### Osservazioni

Durante la clonazione di una diapositiva tra presentazioni differenti, anche il master della diapositiva può essere clonato. Un registro interno è utilizzato per tenere traccia dei master clonati automaticamente, impedendo la creazione di più cloni dello stesso master. La clonazione manuale dei master non sarà né impedita né registrata. Se è necessario un controllo maggiore sul processo di clonazione, utilizzare [`InsertClone`](../insertclone) o [`InsertClone`](../insertclone) per clonare le diapositive e [`AddClone`](../../imasterslidecollection/addclone) per clonare i master.

### Esempi

```csharp
[C#]
// Istanziare la classe Presentation che rappresenta un file di presentazione
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Clona la diapositiva desiderata alla fine della raccolta di diapositive nella stessa presentazione
    ISlideCollection slds = pres.Slides;
    // Clona la diapositiva desiderata all'indice specificato nella stessa presentazione
    slds.InsertClone(2, pres.Slides[1]);
    // Scrivi la presentazione modificata su disco
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

Il seguente esempio mostra come clonare in un'altra posizione all'interno della Presentazione.

```csharp
[C#]
// Istanziare la classe Presentation per caricare il file di presentazione sorgente
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Istanziare la classe Presentation per il PPTX di destinazione (dove la diapositiva deve essere clonata)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Scrivi la presentazione di destinazione su disco
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Vedi anche

* interfaccia [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Indice della nuova diapositiva. |
| sourceSlide | ISlide | Diapositiva da clonare. |
| destLayout | ILayoutSlide | Layout della diapositiva per una nuova diapositiva. |

### Valore di ritorno

Diapositiva inserita.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ILayoutSlide](../../ilayoutslide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Inserisce una copia di una diapositiva sorgente specificata nella posizione specificata della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) oppure verrà generata un'eccezione PptxEditException (se allowCloneMissingLayout è false).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Indice della nuova diapositiva. |
| sourceSlide | ISlide | Diapositiva da clonare. |
| destMaster | IMasterSlide | Master slide per una nuova diapositiva. |
| allowCloneMissingLayout | Boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) oppure verrà generata un'eccezione PptxEditException (se allowCloneMissingLayout è false). |

### Valore di ritorno

Diapositiva inserita.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanciata se non esiste un layout appropriato nel master specificato e allowCloneMissingLayout è false. |

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IMasterSlide](../../imasterslide)
* classe [SlideCollection](../../slidecollection)
* spazio dei nomi [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->