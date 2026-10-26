---
title: "System::StringExtra"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 911
url: /fr/system.stringextra/
---
## Fonctions

| Fonction | Description |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Concatène le tableau de chaînes. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatène des chaînes. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatène des chaînes. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatène des chaînes. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Convertit plusieurs objets en chaîne et concatène les chaînes résultantes. Spécialisation pour les types [SmartPtr](../system/smartptr/). |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Convertit plusieurs objets en chaîne et concatène les chaînes résultantes. Spécialisation pour les types arithmétiques. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Convertit plusieurs objets en chaîne et concatène les chaînes résultantes. Spécialisation pour les structures et autres types de valeur. |