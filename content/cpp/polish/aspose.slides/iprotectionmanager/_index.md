---
title: IProtectionManager
second_title: Odwołanie do API Aspose.Slides dla C++
description: Zarządzanie ochroną hasłem prezentacji.
type: docs
weight: 3459
url: /pl/aspose.slides/iprotectionmanager/
---
## IProtectionManager klasa


[Presentation](../presentation/) zarządzanie ochroną hasła.

```cpp
class IProtectionManager : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) | Określa, czy prezentacja jest chroniona hasłem w celu modyfikacji. |
| virtual void [Encrypt](./encrypt/)([System::String](../../system/string/)) | Szyfruje [Presentation](../presentation/) przy użyciu określonego hasła. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() | Ta właściwość ma sens, jeśli prezentacja jest chroniona hasłem. Jeśli prawda, właściwości dokumentu są szyfrowane w pliku prezentacji. Jeśli fałsz, właściwości dokumentu są publiczne, podczas gdy prezentacja jest szyfrowana. Odczyt **bool**. |
| virtual [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() | Zwraca hasło szyfrowania. Tylko do odczytu [System::String](../../system/string/). |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() | Pobiera wartość wskazującą, czy ta instancja jest zaszyfrowana. Tylko do odczytu **bool**. |
| virtual **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() | Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem i właściwości dokumentu tego pliku są publiczne. Wartość prawda oznacza, że tylko właściwości dokumentu są ładowane z zaszyfrowanego pliku prezentacji bez użycia hasła. Wartość fałsz oznacza, że cała zaszyfrowana prezentacja jest ładowana przy użyciu prawidłowego hasła, nie tylko właściwości dokumentu. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze fałsz. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne, wartość właściwości jest zawsze fałsz. Jeśli PresentationEx.EncryptDocumentProperties jest prawda, wartość właściwości IsOnlyDocumentPropertiesLoaded jest zawsze fałsz. Tylko do odczytu **bool**. |
| virtual **bool** [get_IsWriteProtected](./get_iswriteprotected/)() | Pobiera wartość wskazującą, czy ta prezentacja jest chroniona przed zapisem. Tylko do odczytu **bool**. |
| virtual **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() | Pobiera rekomendację tylko do odczytu. Odczyt **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [RemoveEncryption](./removeencryption/)() | Usuwa szyfrowanie. |
| virtual void [RemoveWriteProtection](./removewriteprotection/)() | Usuwa ochronę przed zapisem dla tej prezentacji. |
| virtual void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) | Ta właściwość ma sens, jeśli prezentacja jest chroniona hasłem. Jeśli prawda, właściwości dokumentu są szyfrowane w pliku prezentacji. Jeśli fałsz, właściwości dokumentu są publiczne, podczas gdy prezentacja jest szyfrowana. Zapis **bool**. |
| virtual void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) | Ustawia rekomendację tylko do odczytu. Zapis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| virtual void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) | Ustawia ochronę przed zapisem dla tej prezentacji przy użyciu określonego hasła. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)