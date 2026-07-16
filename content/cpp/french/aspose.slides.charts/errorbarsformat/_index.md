---
title: ErrorBarsFormat
second_title: Référence API Aspose.Slides pour C++
description: "Représente les barres d'erreur des séries de graphiques. Les valeurs personnalisées d'ErrorBars se trouvent dans IChartDataPointCollection (dans la propriété IChartDataPoint::get_ErrorBarsCustomValues())."
type: docs
weight: 482
url: /fr/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat classe

Représente les barres d'erreur des séries de graphiques. Les valeurs personnalisées d'ErrorBars sont dans [IChartDataPointCollection](../ichartdatapointcollection/) (dans la propriété [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/)).

```cpp
class ErrorBarsFormat : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartSeries>>,
                        public Aspose::Slides::Charts::IErrorBarsFormat
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pour des besoins internes uniquement. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Renvoie le graphique parent. Lecture seule [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Représente le format des barres d'erreur. Lecture [IFormat](../iformat/). |
| **bool** [get_HasEndCap](./get_hasendcap/)() override | Spécifie qu'une chute d'extrémité n'est pas dessinée sur les barres d'erreur. Lecture **bool**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Obtient la visibilité des barres d'erreur. Lecture **bool**. |
| [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() override | Obtient le type des barres d'erreur. Lecture [ErrorBarType](../errorbartype/). |
| **float** [get_Value](./get_value/)() override | Obtient la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. Dans tout autre cas, renverra NaN. Lecture **float**. |
| [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() override | Représente les manières possibles de déterminer la longueur des barres d'erreur. Dans le cas d'un type de valeur personnalisé, utilisez la propriété [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) du point de données spécifique dans la collection DataPoints de la série pour spécifier la valeur. Dans le cas des types de valeur Fixed, Percentage ou StandardDeviation, utilisez la propriété Value pour spécifier la valeur.  

Lecture [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Représente le format des barres d'erreur. Écriture [IFormat](../iformat/). |
| void [set_HasEndCap](./set_hasendcap/)(**bool**) override | Spécifie qu'une chute d'extrémité n'est pas dessinée sur les barres d'erreur. Écriture **bool**. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Définit la visibilité des barres d'erreur. Écriture **bool**. |
| void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) override | Définit le type des barres d'erreur. Écriture [ErrorBarType](../errorbartype/). |
| void [set_Value](./set_value/)(**float**) override | Définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. Dans tout autre cas, renverra NaN. Écriture **float**. |
| void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) override | Représente les manières possibles de déterminer la longueur des barres d'erreur. Dans le cas d'un type de valeur personnalisé, utilisez la propriété [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) du point de données spécifique dans la collection DataPoints de la série pour spécifier la valeur. Dans le cas des types de valeur Fixed, Percentage ou StandardDeviation, utilisez la propriété Value pour spécifier la valeur.  

Écriture [ErrorBarValueType](../errorbarvaluetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode [Object.ToString()](../../system/object/tostring/) de C#. Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [IErrorBarsFormat](../ierrorbarsformat/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)