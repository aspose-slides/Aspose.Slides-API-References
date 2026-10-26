---
title: get_GridSpacing()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la spaziatura della griglia che dovrebbe essere usata per la griglia sottostante il documento della presentazione, in punti. Lettura float.
type: docs
weight: 92
url: /it/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() metodo

Restituisce la spaziatura della griglia che dovrebbe essere usata per la griglia sottostante il documento della presentazione, in punti. Lettura **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Osservazioni

La spaziatura della griglia deve essere un numero positivo. L'intervallo tipico è da 1 mm (2.8349607 punti) a 2 pollici (144 punti).

Il seguente codice di esempio mostra come modificare la spaziatura della griglia in una presentazione PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [IViewProperties](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)