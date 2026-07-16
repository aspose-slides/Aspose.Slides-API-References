---
title: CultureInfo
second_title: Référence de l'API Aspose.Slides pour C++
description: "Collection de valeurs et d'algorithmes spécifiques à la culture. Les opérations de définition ne sont activées que sur des objets non en lecture seule. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 53
url: /fr/system.globalization/cultureinfo/
---
## CultureInfo classe

Collection de valeurs et d'algorithmes spécifiques à la culture. Les opérations de définition ne sont activées que sur des objets non en lecture seule. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | Rafraîchit les informations de culture mises en cache. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clone les informations de culture. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | Crée une culture à partir d'un nom. |
| explicit  [CultureInfo](./cultureinfo/)(int) | Informations RTTI. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | Constructeur. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | Constructeur. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | Constructeur. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | Toujours lève ArgumentNullException. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compare les objets. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | Obtient le calendrier utilisé par la culture. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | Obtient le comparateur de chaînes respectant les règles de la culture. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | Obtient l'ensemble bit à bit des types de culture décrivant la culture actuelle. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | Obtient la culture définie pour le thread actuel. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | Obtient la culture UI du thread actuel. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | Obtient les informations de format de date. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Obtient la culture par défaut dans le domaine d'application actuel. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Obtient la culture UI par défaut dans le domaine d'application actuel. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Obtient le nom d'affichage de la culture. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Obtient le nom anglais de la culture. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Obtient le nom RFC 4646 d'une langue. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | Obtient la culture installée avec le système d'exploitation. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | Obtient la culture invariable. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | Vérifie si la culture est neutre. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Vérifie si l'objet culture est en lecture seule. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Obtient l'identifiant de locale d'entrée actif. |
| virtual int [get_LCID](./get_lcid/)() const | Obtient l'identifiant de la culture. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Obtient le nom de la culture. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Obtient le nom natif de la culture. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | Obtient les informations de format numérique. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | Liste des calendriers pouvant être utilisés avec la culture. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | Obtient la culture parente. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | Obtient les paramètres de texte utilisés par la culture. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Obtient le code langue ISO 639-2 à trois lettres. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Obtient le code à trois lettres de la langue tel que défini dans l'API [Windows](../../system.windows/). |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Obtient le nom de langue ISO à deux lettres associé à la culture. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | Obtient un indicateur indiquant si le [CultureInfo](./) utilise les paramètres de culture sélectionnés par l'utilisateur. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Obtient une culture alternative adaptée aux applications console. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | Obtient la culture par son nom. Identique à CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Obtient la culture par son nom. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | Obtient la culture par identifiant. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | Obsolète. Obtient un objet [CultureInfo](./) en lecture seule par le tag de langue RFC 4646 spécifié. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | Obtient les cultures correspondant aux types spécifiés. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Obtient l'objet de format pour un type spécifique. |
| int [GetHashCode](./gethashcode/)() const override | Renvoie le code de hachage de l'objet. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| **bool** [IsInherited](./isinherited/)() const | Obtient le drapeau hérité. POUR USAGE INTERNE. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise juste le nouvel objet et permet la copie-construction des sous-classes. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise juste le nouvel objet et permet la copie-construction des sous-classes. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | Compare les paramètres de culture. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Obtient une version en lecture seule de la culture. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Définit la culture pour le thread actuel. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Définit la culture UI du thread actuel. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | Définit les informations de format de date. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Définit la culture par défaut dans le domaine d'application actuel. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Définit la culture UI par défaut dans le domaine d'application actuel. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Obtient les informations de format numérique. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Convertit la culture en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Classe [IFormatProvider](../../system/iformatprovider/)
* Classe [ICloneable](../../system/icloneable/)
* Espace de noms [System::Globalization](../)
* Bibliothèque [Aspose.Slides](../../)