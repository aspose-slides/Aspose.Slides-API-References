---
title: CreateCustomTimeZone()
second_title: Référence de l'API Aspose.Slides for C++
description: Crée un fuseau horaire personnalisé.
type: docs
weight: 105
url: /fr/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method

Crée un fuseau horaire personnalisé.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifiant du fuseau horaire. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalle de temps entre l'heure standard du fuseau horaire actuel et le temps UTC. |
| display_name | const [String](../../string/)\& | Nom d'affichage. |
| standard_display_name | const [String](../../string/)\& | Nom de l'heure standard. |
| daylight_display_name | const [String](../../string/)\& | Nom de l'heure d'été. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) de règles d'ajustement. |
| disable_daylight_saving_time | **bool** | Vrai pour ignorer toute information d'heure d'été présente dans adjustment_rules. |

### Valeur de retour

Nouveau fuseau horaire.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method

Crée un fuseau horaire personnalisé.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifiant du fuseau horaire. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalle de temps entre l'heure standard du fuseau horaire actuel et le temps UTC. |
| display_name | const [String](../../string/)\& | Nom d'affichage. |
| standard_display_name | const [String](../../string/)\& | Nom de l'heure standard. |
| daylight_display_name | const [String](../../string/)\& | Nom de l'heure d'été. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) de règles d'ajustement. |

### Valeur de retour

Nouveau fuseau horaire.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method

Crée un fuseau horaire personnalisé.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifiant du fuseau horaire. |
| base_utc_offset | [TimeSpan](../../timespan/) | Intervalle de temps entre l'heure standard du fuseau horaire actuel et le temps UTC. |
| display_name | const [String](../../string/)\& | Nom d'affichage. |
| standard_display_name | const [String](../../string/)\& | Nom de l'heure standard. |

### Valeur de retour

Nouveau fuseau horaire.

## Voir aussi

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Classe [String](../../string/)
* Classe [TimeSpan](../../timespan/)
* Classe [TimeZoneInfo](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)