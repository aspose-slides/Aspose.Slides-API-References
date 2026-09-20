---
title: TextFrameFormat class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/textframeformat/
---
## TextFrameFormat třída

Obsahuje vlastnosti formatTextFrameFormatting objektu TextFrame.

**Inheritance:**[`TextFrameFormat`](/slides/python-net/cs/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ TextFrameFormat vystavuje následující členy:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/textframeformat/__init__/#) | Inicializuje novou instanci třídy [`TextFrameFormat`](/slides/python-net/cs/aspose.slides/textframeformat). |

## Properties

| Property | Description |
| :- | :- |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/textframeformat/three_d_format/) | Vrací objekt ThreeDFormat, který představuje vlastnosti 3d efektu pro text.<br/>            Pouze pro čtení [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/cs/aspose.slides/textframeformat/margin_left/) | Vrací nebo nastavuje levý okraj (points) v TextFrame.<br/>            Číst/zapisovat **float**. |
| [`margin_right`](/slides/python-net/cs/aspose.slides/textframeformat/margin_right/) | Vrací nebo nastavuje pravý okraj (points) v TextFrame.<br/>            Číst/zapisovat **float**. |
| [`margin_top`](/slides/python-net/cs/aspose.slides/textframeformat/margin_top/) | Vrací nebo nastavuje horní okraj (points) v TextFrame.<br/>            Číst/zapisovat **float**. |
| [`margin_bottom`](/slides/python-net/cs/aspose.slides/textframeformat/margin_bottom/) | Vrací nebo nastavuje spodní okraj (points) v TextFrame.<br/>            Číst/zapisovat **float**. |
| [`wrap_text`](/slides/python-net/cs/aspose.slides/textframeformat/wrap_text/) | **True** pokud je text zalomený na okrajích TextFrame.<br/>            Číst/zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/cs/aspose.slides/textframeformat/anchoring_type/) | Vrací nebo nastavuje vertikální kotevní text v TextFrame.<br/>            Číst/zapisovat [`TextAnchorType`](/slides/python-net/cs/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/cs/aspose.slides/textframeformat/center_text/) | Pokud NullableBool.True, text by měl být vodorovně vycentrován v rámečku.<br/>            Číst/zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/cs/aspose.slides/textframeformat/text_vertical_type/) | Určuje orientaci textu.<br/>            Výsledná hodnota vizuální rotace textu shrnutá z této vlastnosti a vlastního úhlu<br/>            ve vlastnosti RotationAngle.<br/>            Číst/zapisovat [`TextVerticalType`](/slides/python-net/cs/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/cs/aspose.slides/textframeformat/autofit_type/) | Vrací nebo nastavuje režim automatického přizpůsobení textu.<br/>            Číst/zapisovat [`TextAutofitType`](/slides/python-net/cs/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/cs/aspose.slides/textframeformat/column_count/) | Vrací nebo nastavuje počet sloupců v textové oblasti.<br/>            Tato hodnota musí být kladné číslo. V opačném případě bude nastavena na nulu. <br/>            Hodnota 0 znamená nedefinovanou hodnotu.<br/>            Číst/zapisovat **int**. |
| [`column_spacing`](/slides/python-net/cs/aspose.slides/textframeformat/column_spacing/) | Vrací nebo nastavuje odstup mezi sloupci textu v textové oblasti (v bodech). Toto by se mělo použít <br/>            pouze když je přítomno více než 1 sloupec.<br/>            Tato hodnota musí být kladné číslo. V opačném případě bude nastavena na nulu. <br/>            Číst/zapisovat **float**. |
| [`rotation_angle`](/slides/python-net/cs/aspose.slides/textframeformat/rotation_angle/) | Určuje vlastní rotaci, která je aplikována na text uvnitř ohraničujícího rámečku. Pokud není<br/>            specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, aplikuje se<br/>            nezávisle na tvaru. To znamená, že tvar může mít rotaci a zároveň text sám může mít rotaci.<br/>            Výsledná hodnota vizuální rotace textu je souhrnem této vlastnosti a předdefinovaného<br/>            vertikálního typu ve vlastnosti TextVerticalType.<br/>            Číst/zapisovat **float**. |
| [`transform`](/slides/python-net/cs/aspose.slides/textframeformat/transform/) | Vrací nebo nastavuje tvar zalamování textu.<br/>            Číst/zapisovat [`TextShapeType`](/slides/python-net/cs/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/cs/aspose.slides/textframeformat/keep_text_flat/) | Vrací nebo nastavuje zachování plochého textu i při aplikaci 3-D rotace.<br/>            Číst/zapisovat **bool**. |
| [`slide`](/slides/python-net/cs/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/cs/aspose.slides/textframeformat/text_style/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/cs/aspose.slides/textframeformat/get_effective/#) | Vrací data efektivního formátování textového rámce s aplikovanou dědičností. |


### See Also
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* třída [`TextFrameFormat`](/slides/python-net/cs/aspose.slides/textframeformat)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)