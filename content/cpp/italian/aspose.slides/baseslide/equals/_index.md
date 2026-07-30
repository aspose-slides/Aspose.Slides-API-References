---
title: Equals()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se le due istanze IBaseSlide sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad esempio SlideId, e del contenuto dinamico, ad esempio il valore della data corrente nel Date Placeholder.
type: docs
weight: 170
url: /it/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metodo

Determina se le due istanze [IBaseSlide](../../ibaseslide/) sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad esempio SlideId, e del contenuto dinamico, ad esempio il valore della data corrente nella classe Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | Il [IBaseSlide](../../ibaseslide/) da confrontare con l'attuale [IBaseSlide](../../ibaseslide/). |

### Valore di ritorno

**true** se lo [IBaseSlide](../../ibaseslide/) specificato è uguale all'attuale [IBaseSlide](../../ibaseslide/); altrimenti, **false**.

## Osservazioni

Il seguente esempio mostra come confrontare due diapositive. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBaseSlide](../../ibaseslide/)
* Classe [BaseSlide](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)