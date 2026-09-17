---
title: IChartData class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdata/
---
## IChartData classe

Représente les données utilisées pour le tracé d'un graphique.

Le type IChartData expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/fr/aspose.slides.charts/ichartdata/chart_data_workbook/) | Obtient la fabrique de cellules pour créer les cellules utilisées pour les séries ou les catégories du graphique.<br/>            Lecture seule [`IChartDataWorkbook`](/slides/python-net/fr/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/fr/aspose.slides.charts/ichartdata/series/) | Obtient les séries.<br/>            Lecture seule [`IChartSeriesCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/fr/aspose.slides.charts/ichartdata/series_groups/) | Obtient les groupes de séries.<br/>            Lecture seule [`IChartSeriesGroupCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories/) | Obtient les catégories principales (ou les catégories principales et secondaires <br/>            si la propriété [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) est false).<br/>            Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories/) | Si false alors la propriété [`IChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories) renvoie None et les données <br/>            dans la propriété [`IChartData.categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories) sont utilisées à la fois pour les séries principales et secondaires.<br/>            Si true alors les données dans la propriété [`IChartData.secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories) sont utilisées pour les séries secondaires et les données <br/>            dans la propriété [`IChartData.categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/categories) sont utilisées pour les séries principales.<br/>            Lecture/écriture **bool**. |
| [`secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/secondary_categories/) | Obtient les catégories secondaires si la propriété [`IChartData.use_secondary_categories`](/slides/python-net/fr/aspose.slides.charts/ichartdata/use_secondary_categories) est true.<br/>            Lecture seule [`IChartCategoryCollection`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/fr/aspose.slides.charts/ichartdata/data_source_type/) | Représente la source de données du graphique |
| [`external_workbook_path`](/slides/python-net/fr/aspose.slides.charts/ichartdata/external_workbook_path/) | Représente le chemin du classeur externe si la source de données est externe, None sinon |
| [`embedded_workbook_type`](/slides/python-net/fr/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Obtient le type du classeur intégré.<br/>            Renvoie [`WorkbookType.NOT_DEFINED`](/slides/python-net/fr/aspose.slides.charts/workbooktype/NOT_DEFINED) si [`IChartData.data_source_type`](/slides/python-net/fr/aspose.slides.charts/ichartdata/data_source_type) est <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fr/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Lecture seule [`WorkbookType`](/slides/python-net/fr/aspose.slides.charts/workbooktype). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/fr/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Définit le classeur externe comme source de données pour le graphique. Les données du graphique seront mises à jour à partir du classeur cible. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/fr/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Définit le classeur externe comme source de données pour le graphique. |
| [`read_workbook_stream(self)`](/slides/python-net/fr/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Écrit le classeur Excel intégré dans un flux en mémoire. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/fr/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Initialise le classeur Excel intégré avec la valeur spécifiée par l'utilisateur. |
| [`set_range(self, formula)`](/slides/python-net/fr/aspose.slides.charts/ichartdata/set_range/#str) | Définit la plage de données du graphique. Les séries et les catégories seront mises à jour en fonction de la nouvelle plage de données.<br/>            Si le nombre de séries dans la plage de données est supérieur au nombre de séries dans les données du graphique, alors des séries supplémentaires du même type<br/>            que la dernière série de la collection actuelle seront ajoutées à la fin de la collection. |
| [`get_range(self)`](/slides/python-net/fr/aspose.slides.charts/ichartdata/get_range/#) | Obtient la plage de données du graphique. |
| [`switch_row_column(self)`](/slides/python-net/fr/aspose.slides.charts/ichartdata/switch_row_column/#) | Échange les données sur l'axe.<br/>            Les données tracées sur l'axe X seront déplacées vers l'axe Y et inversement. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)