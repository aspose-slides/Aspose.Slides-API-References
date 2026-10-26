---
title: Rotation3D
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta la rotazione 3D di un grafico.
type: docs
weight: 1327
url: /it/aspose.slides.charts/rotation3d/
---
## Rotation3D classe

Rappresenta la rotazione 3D di un grafico.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti utilizzando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Restituisce la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). Leggi **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Specifica l'altezza di un grafico 3D come percentuale della larghezza del grafico (tra 5 e 500 percento). Leggi **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Restituisce il valore di prospettiva (angolo del campo visivo) per i grafici 3D (tra 0 e 240). Ignorato se il valore della proprietà RightAngleAxes è true. Leggi **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Determina se gli assi del grafico sono a angoli retti, piuttosto che disegnati in prospettiva. In altre parole determina se gli angoli degli assi del grafico sono indipendenti dalla rotazione o dall'elevazione del grafico. Leggi **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Restituisce il grado di rotazione intorno all'asse X, cioè nella direzione Y per i grafici 3D (tra -90 e 90 gradi). La proprietà corrisponde all'elemento 21.2.2.157 rotX (Rotazione X) in ECMA-376 e all'opzione \"Y Rotation\" in PowerPoint 2007+. Leggi **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Restituisce il grado di rotazione intorno all'asse Y, cioè nella direzione X per i grafici 3D (tra 0 e 360 gradi). La proprietà corrisponde all'elemento 21.2.2.158 rotY (Rotazione Y) in ECMA-376 e all'opzione \"X Rotation\" in PowerPoint 2007+. Leggi **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie nelle subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie nelle subclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). Scrivi **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Specifica l'altezza di un grafico 3D come percentuale della larghezza del grafico (tra 5 e 500 percento). Scrivi **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Imposta il valore di prospettiva (angolo del campo visivo) per i grafici 3D (tra 0 e 240). Ignorato se il valore della proprietà RightAngleAxes è true. Scrivi **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Determina se gli assi del grafico sono a angoli retti, piuttosto che disegnati in prospettiva. In altre parole determina se gli angoli degli assi del grafico sono indipendenti dalla rotazione o dall'elevazione del grafico. Scrivi **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Imposta il grado di rotazione intorno all'asse X, cioè nella direzione Y per i grafici 3D (tra -90 e 90 gradi). La proprietà corrisponde all'elemento 21.2.2.157 rotX (Rotazione X) in ECMA-376 e all'opzione \"Y Rotation\" in PowerPoint 2007+. Scrivi **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Imposta il grado di rotazione intorno all'asse Y, cioè nella direzione X per i grafici 3D (tra 0 e 360 gradi). La proprietà corrisponde all'elemento 21.2.2.158 rotY (Rotazione Y) in ECMA-376 e all'opzione \"X Rotation\" in PowerPoint 2007+. Scrivi **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointers o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointers o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IRotation3D](../irotation3d/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)