---
title: IMasterSlide
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta una diapositiva master in una presentazione.
type: docs
weight: 2926
url: /it/aspose.slides/imasterslide/
---
## IMasterSlide classe


Rappresenta una diapositiva master in una presentazione.

```cpp
class IMasterSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IMasterThemeable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](./)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) | Crea una nuova diapositiva master basata su quella corrente, applicando un tema esterno e applica la diapositiva master creata a tutte le diapositive dipendenti. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Restituisce un tema effettivo per questo oggetto temabile. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | Determina se le due istanze [IBaseSlide](../ibaseslide/) sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori di identificatore univoco, ad esempio SlideId, e del contenuto dinamico, ad esempio il valore della data corrente in Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di punti flottanti in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di punti flottanti in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | Restituisce lo sfondo della diapositiva. Solo lettura [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() | Restituisce lo stile di un testo del corpo. Solo lettura [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | Restituisce il controllo ActiveX all'indice specificato. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | Restituisce la raccolta di controlli ActiveX su una diapositiva. Solo lettura [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | Restituisce i dati personalizzati della diapositiva. Solo lettura [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | Restituisce una raccolta di guide di disegno per la diapositiva master. Solo lettura [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva master. Solo lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | Restituisce il gestore HeaderFooter della diapositiva master. Solo lettura [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | Fornisce un facile accesso ai collegamenti ipertestuali contenuti. Solo lettura [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | Restituisce la diapositiva di layout figlia per questa diapositiva master all'indice specificato. Solo lettura [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | Restituisce la raccolta di diapositive di layout figlie per questa diapositiva master. Solo lettura [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | Restituisce il nome di una diapositiva. Lettura [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() | Restituisce lo stile di un altro testo. Solo lettura [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Solo lettura [IPresentation](../ipresentation/). |
| virtual **bool** [get_Preserve](./get_preserve/)() | Determina se il master corrispondente viene cancellato quando tutte le diapositive che lo seguono vengono eliminate. Nota: [Aspose.Slides](../) non rimuoverà mai alcun master inutilizzato da solo; per rimuovere effettivamente i master inutilizzati chiamare [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/) Lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | Restituisce la forma all'indice specificato. Solo lettura [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | Restituisce le forme di una diapositiva. Solo lettura [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | Specifica se le forme sulla diapositiva master debbano essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre **false**. Lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Restituisce la diapositiva base. Solo lettura [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | Restituisce l'ID di una diapositiva. Solo lettura **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | Restituisce l'oggetto TransitionEx che contiene informazioni su come avanza la diapositiva specificata durante una presentazione. Solo lettura [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | Restituisce il gestore del tema master. Solo lettura [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | Restituisce l'oggetto timeline dell'animazione. Solo lettura [IAnimationTimeLine](../ianimationtimeline/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() | Restituisce lo stile di un testo del titolo. Solo lettura [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | Restituisce un array con tutte le diapositive che dipendono da questa diapositiva master. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo [Object.GetHashCode()](../../system/object/gethashcode/) di C#. Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata [System.Object.GetType()](../../system/object/gettype/) di C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore 'is' di C#. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | Unisce le sequenze con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo [Object.MemberwiseClone()](../../system/object/memberwiseclone/) di C#. Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, ma semplicemente inizializza un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, ma semplicemente inizializza un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso di un valore specificato. |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | Imposta il nome di una diapositiva. Scrivi [System::String](../../system/string/). |
| virtual void [set_Preserve](./set_preserve/)(**bool**) | Determina se il master corrispondente viene cancellato quando tutte le diapositive che lo seguono vengono eliminate. Nota: [Aspose.Slides](../) non rimuoverà mai alcun master inutilizzato da solo; per rimuovere effettivamente i master inutilizzati chiamare [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/) Scrivi **bool**. |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | Specifica se le forme sulla diapositiva master debbano essere mostrate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre **false**. Scrivi **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n'th argomento template a un puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore attuale del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo [Object.ToString()](../../system/object/tostring/) di C#. Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruttura C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IBaseSlide](../ibaseslide/)
* Classe [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)