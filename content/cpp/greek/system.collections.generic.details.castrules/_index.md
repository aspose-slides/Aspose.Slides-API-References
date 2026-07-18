---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides για το API C++
description: 
type: docs
weight: 365
url: /el/system.collections.generic.details.castrules/
---
## Δομές

| Struct | Description |
| --- | --- |
| [CastType](./casttype/) | Περιέχει τις συναρτήσεις για τον προσδιορισμό του τύπου μετατροπής. |
## Συναρτήσεις

| Function | Description |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Μετατρέπει τον τύπο πηγής στο τύπο αποτελέσματος. Χρησιμοποιείται όταν οι τύποι πηγής και αποτελέσματος είναι οι ίδιοι. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Μετατρέπει τον τύπο πηγής στο τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος πηγής μπορεί να μετατραπεί στατικά στον τύπο αποτελέσματος. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Μετατρέπει τον τύπο πηγής στο τύπο αποτελέσματος. Χρησιμοποιείται όταν οι τύποι δεν είναι οι ίδιοι και ο τύπος πηγής δεν μπορεί να μετατραπεί στατικά στον τύπο αποτελέσματος. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Μετατρέπει τον τύπο πηγής στο τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος πηγής προορίζεται για boxing στην κλάση [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Μετατρέπει τον τύπο πηγής στο τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος πηγής αφαιρείται από unboxing από την κλάση [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Μετατρέπει τον τύπο πηγής στο τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος πηγής τοποθετείται σε boxing στην κλάση [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Μετατρέπει τον τύπο πηγής στο τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος πηγής αφαιρείται από unboxing από την κλάση [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Μετατρέπει τον τύπο πηγής στο τύπο αποτελέσματος. Χρησιμοποιείται όταν η μετατροπή είναι μη έγκυρη ή η μετατροπή είναι ρητή. |
| **bool** [IsNull](./isnull/)(T) | Ελέγχει ότι η αναπαριστώμενη τιμή είναι nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Ελέγχει ότι η αναπαριστώμενη τιμή είναι nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Ελέγχει ότι η αναπαριστώμενη τιμή είναι nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Ελέγχει την πιθανότητα μετατροπής. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Ελέγχει την πιθανότητα μετατροπής. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Ελέγχει την πιθανότητα μετατροπής. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Ελέγχει την πιθανότητα μετατροπής. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Ελέγχει την πιθανότητα μετατροπής. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Ελέγχει την πιθανότητα μετατροπής. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Ελέγχει την πιθανότητα μετατροπής. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Ελέγχει την πιθανότητα μετατροπής. |