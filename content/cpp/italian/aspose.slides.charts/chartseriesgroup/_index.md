---
title: ChartSeriesGroup
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un gruppo di serie.
type: docs
weight: 300
url: /it/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Rappresenta un gruppo di serie.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, compreso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, compreso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Specifica come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. Leggi [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percento della dimensione predefinita). Leggi **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Restituisce il grafico padre. Solo lettura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Restituisce la serie di grafico nel gruppo all'indice specificato. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Specifica le dimensioni del foro in un grafico a ciambella (può essere tra 0 e 90 percento della dimensione dell'area del grafico). Leggi **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Ottiene l'angolo della prima sezione di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Leggi **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Restituisce la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Leggi **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Specifica lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o colonna. Leggi **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Vero se il grafico ha linee di serie. Applicato a grafici a barre impilate e OfPie. Leggi **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Specifica il formato HiLowLines. HiLowLines applicato con i tipi di grafico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Specifica che ogni marcatore dati nella serie ha un colore diverso. Leggi **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Leggi [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Le informazioni di divisione personalizzate per un grafico pie-of-pie o bar-of-pie con una divisione personalizzata. Restituisce il punto dati che deve essere disegnato nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie per indice. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Le informazioni di divisione personalizzate per un grafico pie-of-pie o bar-of-pie con una divisione personalizzata. Contiene i punti dati che devono essere disegnati nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Solo lettura [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Leggi **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Indica se le serie di questo gruppo sono tracciate su un asse secondario. Solo lettura **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percento). Leggi **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Restituisce una raccolta di serie. Solo lettura [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Restituisce il tipo di questo gruppo di serie. Solo lettura [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Fornisce l'accesso alle barre su/giù di un grafico Line o Stock. Solo lettura [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Ottiene l'elemento all'indice specificato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Specifica come i valori della dimensione delle bolle sono rappresentati nel grafico a bolle. Scrivi [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Specifica il fattore di scala per il grafico a bolle (può essere tra 0 e 300 percento della dimensione predefinita). Scrivi **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Specifica le dimensioni del foro in un grafico a ciambella (può essere tra 0 e 90 percento della dimensione dell'area del grafico). Scrivi **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Imposta l'angolo della prima sezione di un grafico a torta o a ciambella, in gradi (orario dall'alto, da 0 a 360 gradi). Scrivi **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Imposta la distanza, come percentuale della larghezza del marcatore, tra le serie di dati in un grafico 3D. Scrivi **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Specifica lo spazio tra i raggruppamenti di barre o colonne, come percentuale della larghezza della barra o colonna. Scrivi **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Vero se il grafico ha linee di serie. Applicato a grafici a barre impilate e OfPie. Scrivi **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Specifica che ogni marcatore dati nella serie ha un colore diverso. Scrivi **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Specifica come determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. Scrivi [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Specifica un valore da utilizzare per determinare quali punti dati sono nella seconda torta o barra in un grafico pie-of-pie o bar-of-pie. È usato insieme alla proprietà PieSplitBy. Scrivi **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Specifica la dimensione della seconda torta o barra di un grafico pie-of-pie o bar-of-pie, come percentuale della dimensione della prima torta (può essere tra 5 e 200 percento). Scrivi **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento template n-esimo come weak pointer (piuttosto che shared). Consente di cambiare i puntatori nei contenitori in modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni

1) Vedi il riepilogo e le note per la classe ChartSeriesGroupCollection e l'enumerazione CombinableSeriesTypesGroup. 2) Il gruppo di serie contiene alcune proprietà delle serie che sono comuni a ciascuna serie nel gruppo ("series group properties"). Le "series group properties" nella classe [ChartSeriesGroup](./) sono lettura/scrittura. Ognuna delle "series group properties" può avere una proiezione solo lettura nella classe [ChartSeries](../chartseries/).

## Vedi anche

* Classe [IChartSeriesGroup](../ichartseriesgroup/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)