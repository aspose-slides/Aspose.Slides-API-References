---
title: set_GridSpacing()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta la spaziatura della griglia da utilizzare per la griglia alla base del documento della presentazione, in punti. Scrivi float.
type: docs
weight: 105
url: /it/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) metodo

Imposta la spaziatura della griglia che deve essere usata per la griglia alla base del documento della presentazione, in punti. Scrivi **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Osservazioni

Il valore della spaziatura della griglia deve essere un numero positivo. L'intervallo tipico è da 1 mm (2.8349607 punti) a 2 pollici (144 punti).

Il codice di esempio seguente mostra come modificare la spaziatura della griglia in una presentazione PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [ViewProperties](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)