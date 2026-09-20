---
title: Ink class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.ink/ink/
---
## Classe Ink

Rappresenta un oggetto inchiostro su una diapositiva.

**Eredità:**[`Ink`](/slides/python-net/it/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo Ink espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides.ink/ink/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Solo lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides.ink/ink/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Solo lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides.ink/ink/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides.ink/ink/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides.ink/ink/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides.ink/ink/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides.ink/ink/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3d per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà 3d.<br/>            Solo lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides.ink/ink/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Solo lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides.ink/ink/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides.ink/ink/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides.ink/ink/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides.ink/ink/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Solo lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides.ink/ink/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides.ink/ink/z_order_position/) | Restituisce la posizione di una forma nell'ordine z.<br/>            Shapes[0] restituisce la forma in fondo all'ordine z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma in primo piano dell'ordine z.<br/>            Solo lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides.ink/ink/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Solo lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides.ink/ink/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides.ink/ink/x/) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides.ink/ink/y/) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides.ink/ink/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides.ink/ink/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides.ink/ink/black_white_mode/) | La proprietà specifica come una forma verrà renderizzata in modalità bianco-nero..<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides.ink/ink/unique_id/) | Restituisce un identificatore interno, a livello di presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato<br/>            come una chiave univoca persistente.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides.ink/ink/office_interop_shape_id/) | Restituisce un identificatore univoco a livello di diapositiva che rimane costante per tutta la durata della forma e<br/>            consente a PowerPoint o al codice interop di riferirsi alla forma in modo affidabile da qualsiasi punto del documento.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides.ink/ink/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides.ink/ink/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides.ink/ink/name/) | Restituisce o imposta il nome di una forma.<br/>            Non deve essere None. Usa una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides.ink/ink/is_decorative/) | Ottiene o imposta l'opzione 'Segna come decorativo'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides.ink/ink/shape_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides.ink/ink/is_grouped/) | Determina se la forma è raggruppata.<br/>            Solo lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides.ink/ink/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Solo lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides.ink/ink/slide/) | Restituisce la diapositiva genitore di una forma.<br/>            Solo lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides.ink/ink/presentation/) | Restituisce la presentazione genitore di una diapositiva.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/it/aspose.slides.ink/ink/graphical_object_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/it/aspose.slides.ink/ink/traces/) | Ottiene tutti i tracciati contenuti nell'elemento IInk [`IInkTrace`](/slides/python-net/it/aspose.slides.ink/iinktrace).<br/>            Solo lettura. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides.ink/ink/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma è usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Salva il contenuto della Forma come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Forma come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides.ink/ink/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non ne esiste e imposta le proprietà del segnaposto a una specificata. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides.ink/ink/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides.ink/ink/get_visual_bounds/#) | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/it/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Registra un'immagine nella collezione di immagini personalizzate usate per simulare effetti visivi per i pennelli di inchiostro.<br/>            Queste immagini sono usate durante il rendering dell'inchiostro con valori specifici [`InkEffectType`](/slides/python-net/it/aspose.slides.ink/inkeffecttype),<br/>            come Galaxy, Rainbow, ecc. Fornendo le tue immagini, puoi controllare come appare ogni effetto di inchiostro. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/it/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Deregistra un'immagine dalla collezione di immagini personalizzate usate per simulare effetti visivi per i pennelli di inchiostro<br/>            immagini precedentemente registrate via **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Vedi anche
* classe [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject)
* classe [`Ink`](/slides/python-net/it/aspose.slides.ink/ink)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* modulo [`aspose.slides.ink`](/slides/python-net/it/aspose.slides.ink)
* libreria [`Aspose.Slides`](/slides/python-net)