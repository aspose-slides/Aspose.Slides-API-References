---
title: Ink class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ink/ink/
---
## Ink třída

Represents an Ink object on a slide.

**Inheritance:**[`Ink`](/slides/python-net/cs/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/cs/aspose.slides/shape)

The Ink type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides.ink/ink/is_text_holder/) | Určuje, zda je tvar TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/cs/aspose.slides.ink/ink/placeholder/) | Vrací zástupný prvek pro tvar. Vrací None, pokud tvar nemá zástupný prvek.<br/>            Read-only [`IPlaceholder`](/slides/python-net/cs/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/cs/aspose.slides.ink/ink/custom_data/) | Vrací vlastní data tvaru.<br/>            Read-only [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/cs/aspose.slides.ink/ink/raw_frame/) | Vrací nebo nastavuje vlastnosti surového rámečku tvaru.<br/>            Read/write [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/cs/aspose.slides.ink/ink/frame/) | Vrací nebo nastavuje vlastnosti rámečku tvaru.<br/>            Read/write [`IShapeFrame`](/slides/python-net/cs/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/cs/aspose.slides.ink/ink/line_format/) | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti čáry.<br/>            Read-only [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/cs/aspose.slides.ink/ink/three_d_format/) | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají 3D vlastnosti.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/cs/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides.ink/ink/effect_format/) | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti efektu.<br/>            Read-only [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides.ink/ink/fill_format/) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar.<br/>            Poznámka: může vrátit None pro některé typy tvarů, které nemají vlastnosti výplně.<br/>            Read-only [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides.ink/ink/hyperlink_click/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší.<br/>            Read/write [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides.ink/ink/hyperlink_mouse_over/) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší.<br/>            Read/write [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides.ink/ink/hyperlink_manager/) | Vrací správce hypertextových odkazů.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/cs/aspose.slides.ink/ink/hidden/) | Určuje, zda je tvar skrytý.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/cs/aspose.slides.ink/ink/z_order_position/) | Vrací pozici tvaru v z-řazení.<br/>            Shapes[0] vrací tvar na zadní pozici v z-řazení,<br/>            a Shapes[Shapes.Count - 1] vrací tvar na přední pozici v z-řazení.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides.ink/ink/connection_site_count/) | Vrací počet připojovacích míst na tvaru.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/cs/aspose.slides.ink/ink/rotation/) | Vrací nebo nastavuje počet stupňů, o které je specifikovaný tvar otočen kolem z-osy.<br/>            Kladná hodnota značí rotaci po směru hodinových ručiček; záporná hodnota<br/>            značí rotaci proti směru hodinových ručiček.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/cs/aspose.slides.ink/ink/x/) | Získá nebo nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/cs/aspose.slides.ink/ink/y/) | Získá nebo nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/cs/aspose.slides.ink/ink/width/) | Získá nebo nastaví šířku tvaru, měřenou v bodech.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/cs/aspose.slides.ink/ink/height/) | Získá nebo nastaví výšku tvaru, měřenou v bodech.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides.ink/ink/black_white_mode/) | Vlastnost určuje, jak se tvar vykreslí v režimu černobílého zobrazení.<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/cs/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/cs/aspose.slides.ink/ink/unique_id/) | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem.<br/>            Protože tuto hodnotu může uživatel nebo program přepsat, neměla by být považována<br/>            za trvalý jedinečný klíč.<br/>            Read-only **int**.<br/>            Viz také [`Shape.office_interop_shape_id`](/slides/python-net/cs/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides.ink/ink/office_interop_shape_id/) | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a<br/>            umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu.<br/>            Read-only **int**.<br/>            Viz také [`Shape.unique_id`](/slides/python-net/cs/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/cs/aspose.slides.ink/ink/alternative_text/) | Vrací nebo nastavuje alternativní text spojený s tvarem.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides.ink/ink/alternative_text_title/) | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/cs/aspose.slides.ink/ink/name/) | Vrací nebo nastavuje název tvaru.<br/>            Nesmí být None. Použijte prázdný řetězec, pokud je to potřeba.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/cs/aspose.slides.ink/ink/is_decorative/) | Získá nebo nastaví volbu 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/cs/aspose.slides.ink/ink/shape_lock/) | Vrací zámky tvaru.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/cs/aspose.slides.ink/ink/is_grouped/) | Určuje, zda je tvar seskupen.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/cs/aspose.slides.ink/ink/parent_group/) | Vrací objekt GroupShape rodiče, pokud je tvar seskupen. Jinak vrací None.<br/>            Read-only [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/cs/aspose.slides.ink/ink/slide/) | Vrací nadřazený snímek tvaru.<br/>            Read-only [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides.ink/ink/presentation/) | Vrací nadřazenou prezentaci snímku.<br/>            Read-only [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/cs/aspose.slides.ink/ink/graphical_object_lock/) | Vrací zámky tvaru.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/cs/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/cs/aspose.slides.ink/ink/traces/) | Získá všechny stopy obsažené v prvku IInk [`IInkTrace`](/slides/python-net/cs/aspose.slides.ink/iinktrace).<br/>            Read-only. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides.ink/ink/get_image/#) | Vrací miniaturu tvaru.<br/>            Výchozí je typ ShapeThumbnailBounds.Shape pro ohraničení miniatury tvaru. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Vrací miniaturu tvaru. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Uloží obsah tvaru jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Uloží obsah tvaru jako soubor SVG. |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides.ink/ink/remove_placeholder/#) | Definuje, že tento tvar není zástupný prvek. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví vlastnosti zástupného prvku na zadaný. |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides.ink/ink/get_base_placeholder/#) | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn).<br/>            Pokud aktuální tvar není zděděn, vrátí se None. |
| [`get_visual_bounds(self)`](/slides/python-net/cs/aspose.slides.ink/ink/get_visual_bounds/#) | Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/cs/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Zaregistruje obrázek do kolekce vlastních obrázků používaných k simulaci vizuálních efektů pro inkové štětce.<br/>            Tyto obrázky se používají při vykreslování ink s konkrétními hodnotami [`InkEffectType`](/slides/python-net/cs/aspose.slides.ink/inkeffecttype),<br/>            jako je Galaxy, Rainbow atd. Poskytnutím vlastních obrázků můžete ovládat, jak se každý inkový efekt zobrazuje. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/cs/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Zruší registraci obrázku z kolekce vlastních obrázků používaných k simulaci vizuálních efektů pro inkové štětce,<br/>            dříve registrovaných obrázků pomocí **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Viz také
* třída [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* třída [`Ink`](/slides/python-net/cs/aspose.slides.ink/ink)
* třída [`Shape`](/slides/python-net/cs/aspose.slides/shape)
* modul [`aspose.slides.ink`](/slides/python-net/cs/aspose.slides.ink)
* knihovna [`Aspose.Slides`](/slides/python-net)