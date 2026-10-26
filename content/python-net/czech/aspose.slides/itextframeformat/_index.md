---
title: ITextFrameFormat class
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručky API
description: 
type: docs
url: /cs/aspose.slides/itextframeformat/
---
## ITextFrameFormat třída

Obsahuje vlastnosti formátování TextFrame.

Typ ITextFrameFormat poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`text_style`](/slides/python-net/cs/aspose.slides/itextframeformat/text_style/) | Vrací styl textu.<br/>            Pouze ke čtení [`ITextStyle`](/slides/python-net/cs/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/cs/aspose.slides/itextframeformat/margin_left/) | Vrací nebo nastavuje levý okraj (body) v TextFrame.<br/>            Čtení/zápis **float**. |
| [`margin_right`](/slides/python-net/cs/aspose.slides/itextframeformat/margin_right/) | Vrací nebo nastavuje pravý okraj (body) v TextFrame.<br/>            Čtení/zápis **float**. |
| [`margin_top`](/slides/python-net/cs/aspose.slides/itextframeformat/margin_top/) | Vrací nebo nastavuje horní okraj (body) v TextFrame.<br/>            Čtení/zápis **float**. |
| [`margin_bottom`](/slides/python-net/cs/aspose.slides/itextframeformat/margin_bottom/) | Vrací nebo nastavuje dolní okraj (body) v TextFrame.<br/>            Čtení/zápis **float**. |
| [`wrap_text`](/slides/python-net/cs/aspose.slides/itextframeformat/wrap_text/) | **True** pokud je text zalomen na okrajích TextFrame.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/cs/aspose.slides/itextframeformat/anchoring_type/) | Vrací nebo nastavuje vertikální kotvu textu v TextFrame.<br/>            Čtení/zápis [`TextAnchorType`](/slides/python-net/cs/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/cs/aspose.slides/itextframeformat/center_text/) | Pokud NullableBool.True, má být text horizontálně vycentrován v rámečku.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/cs/aspose.slides/itextframeformat/text_vertical_type/) | Určuje orientaci textu.<br/>            Výsledná hodnota vizuální rotace textu shrnutá z této vlastnosti a vlastního úhlu<br/>            v vlastnosti RotationAngle.<br/>            Čtení/zápis [`TextVerticalType`](/slides/python-net/cs/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/cs/aspose.slides/itextframeformat/autofit_type/) | Vrací nebo nastavuje režim automatického přizpůsobení textu.<br/>            Čtení/zápis [`TextAutofitType`](/slides/python-net/cs/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/cs/aspose.slides/itextframeformat/column_count/) | Vrací nebo nastavuje počet sloupců v textové oblasti.<br/>            Tato hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu.<br/>            Hodnota 0 znamená nedefinovanou hodnotu.<br/>            Čtení/zápis **int**. |
| [`column_spacing`](/slides/python-net/cs/aspose.slides/itextframeformat/column_spacing/) | Vrací nebo nastavuje mezeru mezi sloupci textu v textové oblasti (v bodech). Toto by se mělo použít pouze<br/>            pokud je přítomno více než 1 sloupec.<br/>            Tato hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu.<br/>            Čtení/zápis **float**. |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/itextframeformat/three_d_format/) | Vrací objekt ThreeDFormat, který představuje vlastnosti 3D efektu pro text.<br/>            Pouze ke čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/cs/aspose.slides/itextframeformat/keep_text_flat/) | Vrací nebo nastavuje úplné vyloučení textu ze 3D scény.<br/>            Čtení/zápis **bool**. |
| [`rotation_angle`](/slides/python-net/cs/aspose.slides/itextframeformat/rotation_angle/) | Specifikuje vlastní rotaci, která je aplikována na text v rámci ohraničujícího rámečku. Pokud není<br/>            specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, pak je tato<br/>            aplikována nezávisle na tvaru. To znamená, že tvar může mít aplikovanou rotaci navíc<br/>            k rotaci samotného textu.<br/>            Výsledná hodnota vizuální rotace textu shrnutá z této vlastnosti a předdefinovaného<br/>            vertikálního typu ve vlastnosti TextVerticalType.<br/>            Čtení/zápis **float**. |
| [`transform`](/slides/python-net/cs/aspose.slides/itextframeformat/transform/) | Vrací nebo nastavuje tvar zalamování textu.<br/>            Čtení/zápis [`TextShapeType`](/slides/python-net/cs/aspose.slides/textshapetype). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/cs/aspose.slides/itextframeformat/get_effective/#) | Vrací efektivní data formátování textového rámce s aplikovaným děděním. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)