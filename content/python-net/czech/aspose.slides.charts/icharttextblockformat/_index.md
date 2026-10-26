---
title: IChartTextBlockFormat class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat třída

Representuje formátovací vlastnosti pro textové elementy grafu.

Typ IChartTextBlockFormat vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`anchoring_type`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/anchoring_type/) | Vrací nebo nastavuje vertikální kotevní text v TextFrame.<br/>            Číst/zapisovat [`TextAnchorType`](/slides/python-net/cs/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/center_text/) | Pokud NullableBool.True, pak by text měl být horizontálně vycentrován v rámečku.<br/>            Číst/zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/text_vertical_type/) | Určuje orientaci textu.<br/>            Výsledná hodnota vizuální rotace textu je souhrn této vlastnosti a vlastního úhlu<br/>            v vlastnosti RotationAngle.<br/>            Číst/zapisovat [`TextVerticalType`](/slides/python-net/cs/aspose.slides/textverticaltype). |
| [`margin_left`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/margin_left/) | Vrací nebo nastavuje levý okraj (body) v TextFrame.<br/>            Změna této vlastnosti může mít vliv pouze na následující části grafu: <br/>            DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování).<br/>            Číst/zapisovat **float**. |
| [`margin_right`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/margin_right/) | Vrací nebo nastavuje pravý okraj (body) v TextFrame.<br/>            Změna této vlastnosti může mít vliv pouze na následující části grafu: <br/>            DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování).<br/>            Číst/zapisovat **float**. |
| [`margin_top`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/margin_top/) | Vrací nebo nastavuje horní okraj (body) v TextFrame.<br/>            Změna této vlastnosti může mít vliv pouze na následující části grafu: <br/>            DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování).<br/>            Číst/zapisovat **float**. |
| [`margin_bottom`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/margin_bottom/) | Vrací nebo nastavuje spodní okraj (body) v TextFrame.<br/>            Změna této vlastnosti může mít vliv pouze na následující části grafu: <br/>            DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování).<br/>            Číst/zapisovat **float**. |
| [`wrap_text`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/wrap_text/) | **True** pokud je text zalamován na okrajích TextFrame.<br/>            Změna této vlastnosti může mít vliv pouze na následující části grafu: <br/>            DataLabel a DataLabelFormat (plná podpora v PowerPoint 2007/2013).<br/>            Číst/zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`autofit_type`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/autofit_type/) | Vrací nebo nastavuje režim automatického přizpůsobení textu.<br/>            Změna této vlastnosti může mít vliv pouze na následující části grafu: <br/>            DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování).<br/>            Číst/zapisovat [`TextAutofitType`](/slides/python-net/cs/aspose.slides/textautofittype). |
| [`rotation_angle`](/slides/python-net/cs/aspose.slides.charts/icharttextblockformat/rotation_angle/) | Určuje vlastní rotaci, která se použije na text uvnitř ohraničujícího rámečku. Pokud není<br/>            specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, aplikuje se<br/>            nezávisle na tvaru. To znamená, že tvar může mít aplikovanou rotaci a zároveň může mít text<br/>            vlastní rotaci.<br/>            Výsledná hodnota vizuální rotace textu je souhrn této vlastnosti a předdefinovaného<br/>            vertikálního typu ve vlastnosti TextVerticalType.<br/>            Číst/zapisovat **float**. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)