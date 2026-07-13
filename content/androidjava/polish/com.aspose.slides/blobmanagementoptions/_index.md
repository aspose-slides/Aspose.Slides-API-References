---
title: BlobManagementOptions
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje opcje, które mogą być użyte do zarządzania regułami obsługi BLOB oraz innymi ustawieniami BLOB.
type: docs
url: /pl/com.aspose.slides/blobmanagementoptions/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Reprezentuje opcje, które mogą być użyte do zarządzania regułami obsługi BLOB i innymi ustawieniami BLOB.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Tworzy nowe domyślne opcje zarządzania BLOB. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas całego czasu życia instancji. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas całego czasu życia instancji. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Ścieżka główna, w której będą tworzone pliki tymczasowe. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Ścieżka główna, w której będą tworzone pliki tymczasowe. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Tworzy nowe domyślne opcje zarządzania BLOB.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas całego czasu życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane w trakcie życia instancji Presentation.

**Zwraca:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas całego czasu życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane w trakcie życia instancji Presentation.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.

--------------------

Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją.

**Zwraca:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.

--------------------

Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. Proces hostujący powinien mieć uprawnienia do tworzenia tam plików i folderów.

**Zwraca:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. Proces hostujący powinien mieć uprawnienia do tworzenia tam plików i folderów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

--------------------

Ta właściwość jest ignorowana, jeśli \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) jest ustawiona na false, ponieważ wtedy pamięć jest jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOB-ów w pamięci nie ma efektu.

--------------------

Domyślna wartość to 629 145 600 bajtów (600 MB).

--------------------

Można ustawić tę właściwość na zero, ale nadal zostanie zarezerwowana niewielka minimalna ilość pamięci.

**Zwraca:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

--------------------

Ta właściwość jest ignorowana, jeśli \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) jest ustawiona na false, ponieważ wtedy pamięć jest jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOB-ów w pamięci nie ma efektu.

--------------------

Domyślna wartość to 629 145 600 bajtów (600 MB).

--------------------

Można ustawić tę właściwość na zero, ale nadal zostanie zarezerwowana niewielka minimalna ilość pamięci.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |