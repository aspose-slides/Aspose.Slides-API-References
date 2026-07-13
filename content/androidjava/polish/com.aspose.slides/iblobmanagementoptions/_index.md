---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Obiekt BLOB (Binary Large Object) jest danymi binarnymi przechowywanymi jako pojedynczy byt – tj.
type: docs
url: /pl/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Obiekt binarny dużego rozmiaru (BLOB) to dane binarne przechowywane jako pojedynczy byt – np. BLOB może być plikiem audio, wideo lub samą prezentacją. W celu optymalizacji zużycia pamięci przy pracy z BLOB-ami stosuje się różne techniki – zarówno dla BLOB-ów już zapisanych w prezentacji, jak i dodawanych później programowo. Używając [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) możesz zmienić różne aspekty zachowania dotyczące obsługi BLOB-ów dla czasu życia instancji [IPresentation](../../com.aspose.slides/ipresentation).
## Metody

| Metoda | Opis |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas życia instancji. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas życia instancji. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Ta właściwość określa, czy podczas pracy z BLOB-ami można tworzyć pliki tymczasowe, co znacząco zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Ta właściwość określa, czy podczas pracy z BLOB-ami można tworzyć pliki tymczasowe, co znacząco zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Ścieżka główna, w której będą tworzone pliki tymczasowe. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Ścieżka główna, w której będą tworzone pliki tymczasowe. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, jednak źródło (strumień lub plik) nie może być zmienione w trakcie życia instancji Presentation. Oto przykład:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException zostanie rzucony, ponieważ pres.pptx jest zablokowany na cały czas życia obiektu Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // po zwolnieniu obiektu Presentation plik jest odblokowany i może zostać usunięty
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Zwraca:**  
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, jednak źródło (strumień lub plik) nie może być zmienione w trakcie życia instancji Presentation. Oto przykład:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException zostanie rzucony, ponieważ pres.pptx jest zablokowany na cały czas życia obiektu Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // po zwolnieniu obiektu Presentation plik jest odblokowany i może zostać usunięty
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Ta właściwość określa, czy podczas pracy z BLOB-ami można tworzyć pliki tymczasowe, co znacząco zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.

--------------------

Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją.

**Zwraca:**  
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Ta właściwość określa, czy podczas pracy z BLOB-ami można tworzyć pliki tymczasowe, co znacząco zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.

--------------------

Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. Proces hostujący powinien mieć uprawnienia do tworzenia tam plików i folderów.

**Zwraca:**  
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. Proces hostujący powinien mieć uprawnienia do tworzenia tam plików i folderów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po przekroczeniu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

--------------------

Ta właściwość jest ignorowana, jeśli \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) jest ustawiona na false, ponieważ wówczas pamięć jest jedynym dostępnym miejscem przechowywania i ograniczanie użycia BLOB-ów w pamięci nie ma efektu.

--------------------

Domyślna wartość to 629 145 600 bajtów (600 MB).

--------------------

Możesz ustawić tę właściwość na zero, ale nadal zostanie zarezerwowana niewielka minimalna ilość pamięci.

**Zwraca:**  
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po przekroczeniu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

--------------------

Ta właściwość jest ignorowana, jeśli \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) jest ustawiona na false, ponieważ wówczas pamięć jest jedynym dostępnym miejscem przechowywania i ograniczanie użycia BLOB-ów w pamięci nie ma efektu.

--------------------

Domyślna wartość to 629 145 600 bajtów (600 MB).

--------------------

Możesz ustawić tę właściwość na zero, ale nadal zostanie zarezerwowana niewielka minimalna ilość pamięci.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |