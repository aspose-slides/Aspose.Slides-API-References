---
title: CreateCustomTimeZone()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί μια προσαρμοσμένη ζώνη ώρας.
type: docs
weight: 105
url: /el/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) μέθοδος


Δημιουργεί μια προσαρμοσμένη ζώνη ώρας.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | const [String](../../string/)\& | Αναγνωριστικό ζώνης ώρας. |
| base_utc_offset | [TimeSpan](../../timespan/) | Χρονικό διάστημα μεταξύ της τυπικής ώρας της τρέχουσας ζώνης ώρας και της ώρας UTC. |
| display_name | const [String](../../string/)\& | Όνομα εμφάνισης. |
| standard_display_name | const [String](../../string/)\& | Όνομα τυπικής ώρας. |
| daylight_display_name | const [String](../../string/)\& | Όνομα ώρας θερινής ώρας. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) των κανόνων προσαρμογής. |
| disable_daylight_saving_time | **bool** | true για να αγνοηθούν τυχόν πληροφορίες θερινής ώρας που εμφανίζονται στο adjustment_rules. |

### Τιμή Επιστροφής

Νέα ζώνη ώρας.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) μέθοδος


Δημιουργεί μια προσαρμοσμένη ζώνη ώρας.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | const [String](../../string/)\& | Αναγνωριστικό ζώνης ώρας. |
| base_utc_offset | [TimeSpan](../../timespan/) | Χρονικό διάστημα μεταξύ της τυπικής ώρας της τρέχουσας ζώνης ώρας και της ώρας UTC. |
| display_name | const [String](../../string/)\& | Όνομα εμφάνισης. |
| standard_display_name | const [String](../../string/)\& | Όνομα τυπικής ώρας. |
| daylight_display_name | const [String](../../string/)\& | Όνομα ώρας θερινής ώρας. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) των κανόνων προσαρμογής. |

### Τιμή Επιστροφής

Νέα ζώνη ώρας.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) μέθοδος


Δημιουργεί μια προσαρμοσμένη ζώνη ώρας.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | const [String](../../string/)\& | Αναγνωριστικό ζώνης ώρας. |
| base_utc_offset | [TimeSpan](../../timespan/) | Χρονικό διάστημα μεταξύ της τυπικής ώρας της τρέχουσας ζώνης ώρας και της ώρας UTC. |
| display_name | const [String](../../string/)\& | Όνομα εμφάνισης. |
| standard_display_name | const [String](../../string/)\& | Όνομα τυπικής ώρας. |

### Τιμή Επιστροφής

Νέα ζώνη ώρας.

## Δείτε επίσης

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Κλάση [String](../../string/)
* Κλάση [TimeSpan](../../timespan/)
* Κλάση [TimeZoneInfo](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)