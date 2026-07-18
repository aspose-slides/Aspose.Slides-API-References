---
title: PropertyInfo()
second_title: Αναφορά API του Aspose.Slides για C++
description: Κατασκευαστής. Ιδιότητα με μόνο const getter.
type: docs
weight: 66
url: /el/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) Κατασκευαστής


Κατασκευαστής. Ιδιότητα με μόνο const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| PropertyType | Τύπος της ιδιότητας. |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) Κατασκευαστής


Κατασκευαστής. Ιδιότητα με μόνο non-const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| PropertyType | Τύπος της ιδιότητας. |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) Κατασκευαστής


Κατασκευαστής.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| PropertyType | Τύπος της ιδιότητας. |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Μέθοδος setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) Κατασκευαστής


Κατασκευαστής. [Nullable](../../../system/nullable/) ιδιότητα με setter και getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| PropertyType | Τύπος της ιδιότητας. |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Μέθοδος setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) Κατασκευαστής


Κατασκευαστής. [Nullable](../../../system/nullable/) ιδιότητα με μόνο const getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| PropertyType | Τύπος της ιδιότητας. |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Μέθοδος setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) Κατασκευαστής


Κατασκευαστής. [Object](../../../system/object/) ιδιότητα με μόνο getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| PropertyType | Τύπος της ιδιότητας. |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Μέθοδος setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) Κατασκευαστής


Κατασκευάζει πληροφορίες ιδιότητας τύπου string.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Μέθοδος setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) Κατασκευαστής


Κατασκευάζει πληροφορίες ιδιότητας τύπου string από κλάση με const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Μέθοδος setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) Κατασκευαστής


Κατασκευάζει [Decimal](../../../system/decimal/) πληροφορίες ιδιότητας.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Μέθοδος setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) Κατασκευαστής


Κατασκευάζει [Decimal](../../../system/decimal/) πληροφορίες ιδιότητας από κλάση με const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Μέθοδος setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) Κατασκευαστής


Κατασκευάζει πληροφορίες ιδιότητας τύπου boolean.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)(**bool**) | Μέθοδος setter. |
| get_prop_method | **bool**(ClassType::*)() | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) Κατασκευαστής


Κατασκευάζει πληροφορίες ιδιότητας τύπου boolean από κλάση με const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)(**bool**) | Μέθοδος setter. |
| get_prop_method | **bool**(ClassType::*)() const | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) Κατασκευαστής


Κατασκευάζει πληροφορίες ιδιότητας **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Μέθοδος setter. |
| get_prop_method | **int64_t**(ClassType::*)() | Μέθοδος getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) Κατασκευαστής


Κατασκευάζει πληροφορίες ιδιότητας **int64_t** από κλάση με const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| ClassType | Τύπος της κλάσης στην οποία ανήκει η ιδιότητα. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [String](../../../system/string/) | Όνομα της ιδιότητας. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Μέθοδος setter. |
| get_prop_method | **int64_t**(ClassType::*)() const | Μέθοδος getter. |

## Δείτε επίσης

* Class [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [PropertyInfo](../)
* Κλάση [Nullable](../../../system/nullable/)
* Κλάση [Decimal](../../../system/decimal/)
* Χώρος Ονομάτων [System::Reflection](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)