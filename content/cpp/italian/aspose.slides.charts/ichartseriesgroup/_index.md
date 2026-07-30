---
title: IChartSeriesGroup
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un gruppo di serie.
type: docs
weight: 846
url: /it/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup classe


Rappresenta un gruppo di serie.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Specifica come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. Leggi [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percento della dimensione predefinita). Leggi **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Restituisce il grafico. Solo lettura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Restituisce la serie del grafico nel gruppo all'indice specificato. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Specifica la dimensione del foro in un grafico a ciambella (può essere tra 10 e 90 percento della dimensione dell'area del grafico). Leggi **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Ottiene l'angolo della prima fetta di torta o ciambella, in gradi (in senso orario dall'alto, da 0 a 360 gradi). Leggi **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Restituisce la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Leggi **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. Leggi **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Vero se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie. Leggi **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Specifica il formato HiLowLines. HiLowLines è applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Specifica che ogni marcatore dati nella serie ha un colore diverso. Leggi **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Leggi [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | Le informazioni di divisione personalizzate per un grafico pie-of-pie o bar-of-pie con divisione personalizzata. Restituisce il punto dati che deve essere disegnato nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie per indice. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | Le informazioni di divisione personalizzate per un grafico pie-of-pie o bar-of-pie con divisione personalizzata. Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Solo lettura [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Leggi **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Indica se le serie di questo gruppo sono tracciate sull'asse secondario. Solo lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Solo lettura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percento). Leggi **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Restituisce una collezione di serie di grafico in sola lettura. Solo lettura [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Restituisce la diapositiva base. Solo lettura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Restituisce il tipo di questo gruppo di serie. Solo lettura [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Fornisce l'accesso alle barre su/giù di un grafico Line o Stock. Solo lettura [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Ottiene l'elemento all'indice specificato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Specifica come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. Scrivi [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percento della dimensione predefinita). Scrivi **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Specifica la dimensione del foro in un grafico a ciambella (può essere tra 10 e 90 percento della dimensione dell'area del grafico). Scrivi **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Imposta l'angolo della prima fetta di torta o ciambella, in gradi (in senso orario dall'alto, da 0 a 360 gradi). Scrivi **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Scrivi **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Specifica lo spazio tra i gruppi di barre o colonne, come percentuale della larghezza della barra o colonna. Scrivi **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Vero se il grafico ha linee di serie. Applicato ai grafici a barre impilate e OfPie. Scrivi **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Specifica che ogni marcatore dati nella serie ha un colore diverso. Scrivi **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Scrivi [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Scrivi **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percento). Scrivi **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni


1) Vedere il riepilogo e le osservazioni per la classe ChartSeriesGroupCollection e l'enumerazione CombinableSeriesTypesGroup. 2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a ciascuna serie del gruppo ("series group properties"). Le "series group properties" nella classe [ChartSeriesGroup](../chartseriesgroup/) sono lettura/scrittura. Ognuna delle "series group properties" può avere una proiezione solo lettura nella classe [ChartSeries](../chartseries/).

## Vedi anche

* Classe [IChartComponent](../ichartcomponent/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)