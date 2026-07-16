---
title: get_RecoverWorkbookFromChartCache()
second_title: Référence API Aspose.Slides pour C++
description: Si la source de données du graphique est un classeur externe et qu'il n'est pas disponible, il sera récupéré à partir du cache du graphique.
type: docs
weight: 27
url: /fr/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() méthode


Si la source de données du graphique est un classeur externe et qu'il n'est pas disponible, il sera récupéré à partir du cache du graphique.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
```

## Remarques



Exemple : 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## Voir aussi

* Classe [ISpreadsheetOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)