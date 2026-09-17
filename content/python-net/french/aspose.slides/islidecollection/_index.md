---
title: ISlideCollection class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/islidecollection/
---
## ISlideCollection classe

Représente une collection de diapositives.

Le type ISlideCollection expose les membres suivants :

Obtient l’élément à l’index spécifié.
            Lecture seule [`ISlide`](/slides/python-net/fr/aspose.slides/islide).

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/islidecollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/fr/aspose.slides/islidecollection/add_clone/#islide) | Ajoute une copie d’une diapositive spécifiée à la fin de la collection. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/fr/aspose.slides/islidecollection/add_clone/#islide-isection) | Ajoute une copie d’une diapositive spécifiée à la fin de la section spécifiée. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/fr/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Ajoute une copie d’une diapositive spécifiée à la fin de la collection. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/fr/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Ajoute une copie d’une diapositive source spécifiée à la fin de la collection.<br/>            La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié <br/>            (une mise en page appropriée est celle qui a le même Type ou le même Nom que <br/>            la mise en page de la diapositive source). S’il n’existe aucune mise en page appropriée alors <br/>            la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout <br/>            est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout <br/>            est faux). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_clone/#int-islide) | Insère une copie d’une diapositive spécifiée à la position spécifiée de la collection. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Insère une copie d’une diapositive spécifiée à la position spécifiée de la collection. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Insère une copie d’une diapositive source spécifiée à la position spécifiée de la collection.<br/>            La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié <br/>            (une mise en page appropriée est celle qui a le même Type ou le même Nom que <br/>            la mise en page de la diapositive source). S’il n’existe aucune mise en page appropriée alors <br/>            la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout <br/>            est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout <br/>            est faux). |
| [`to_array(self)`](/slides/python-net/fr/aspose.slides/islidecollection/to_array/#) | Crée et renvoie un tableau contenant toutes les diapositives. |
| [`to_array(self, start_index, count)`](/slides/python-net/fr/aspose.slides/islidecollection/to_array/#int-int) | Crée et renvoie un tableau contenant toutes les diapositives de la plage spécifiée. |
| [`reorder(self, index, slide)`](/slides/python-net/fr/aspose.slides/islidecollection/reorder/#int-islide) | Déplace une diapositive de la collection vers la position spécifiée. |
| [`reorder(self, index, slides)`](/slides/python-net/fr/aspose.slides/islidecollection/reorder/#int-listislide) | Déplace des diapositives de la collection vers la position spécifiée.<br/>            Les diapositives seront placées à partir de l’index dans l’ordre où elles apparaissent dans la liste. |
| [`add_from_pdf(self, path)`](/slides/python-net/fr/aspose.slides/islidecollection/add_from_pdf/#str) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/fr/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection en tenant compte des options d’importation PDF. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/fr/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/fr/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/fr/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [`add_from_html(self, html_text)`](/slides/python-net/fr/aspose.slides/islidecollection/add_from_html/#str) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/fr/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [`add_from_html(self, html_stream)`](/slides/python-net/fr/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_from_html/#int-str) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [`add_empty_slide(self, layout)`](/slides/python-net/fr/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Ajoute une nouvelle diapositive vide à la fin de la collection. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/fr/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Insère une copie d’une diapositive spécifiée à la position spécifiée de la collection. |
| [`remove(self, value)`](/slides/python-net/fr/aspose.slides/islidecollection/remove/#islide) | Supprime la première occurrence d’un objet spécifique de la collection. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides/islidecollection/remove_at/#int) | Supprime l’élément à l’index spécifié de la collection. |
| [`index_of(self, slide)`](/slides/python-net/fr/aspose.slides/islidecollection/index_of/#islide) | Renvoie l’index de la diapositive spécifiée dans la collection. |


### Voir aussi
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)