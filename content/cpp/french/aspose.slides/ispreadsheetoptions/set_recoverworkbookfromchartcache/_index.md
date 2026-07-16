---
title: set_RecoverWorkbookFromChartCache()
second_title: Référence de l'API Aspose.Slides pour C++
description: Si la source de données du graphique provient d'un classeur externe et qu'elle n'est pas disponible, elle sera récupérée à partir du cache du graphique.
type: docs
weight: 40
url: /fr/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) méthode


Si la source de données du graphique provient d’un classeur externe et qu’elle n’est pas disponible, elle sera récupérée à partir du cache du graphique.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
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