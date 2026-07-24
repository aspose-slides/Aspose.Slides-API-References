---
title: SymmetricAlgorithm
second_title: "Aspose.Slides für C++ API-Referenz"
description: "Symmetrischer Algorithmus, der denselben Schlüssel für Verschlüsselung und Entschlüsselung verwendet, Basisklasse. Objekte dieser Klasse sollten nur über die System::MakeObject()-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie immer diese Klasse in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben."
type: docs
weight: 651
url: /de/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm Klasse

Symmetrischer Algorithmus, der denselben Schlüssel für Verschlüsselung und Entschlüsselung verwendet, Basisklasse. Objekte dieser Klasse sollten nur über die [System::MakeObject()](../../system/makeobject/)-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie immer diese Klasse in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn Funktionen als Argument zu übergeben.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Erzeugt eine Algorithmusinstanz. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | Erstellt einen Entschlüsseler mit den zum Algorithmusobjekt zugehörigen Parametern. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Erstellt einen Entschlüsseler mit expliziten Parametern. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | Erstellt einen Encryptor mit den zum Algorithmusobjekt zugehörigen Parametern. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Erstellt einen Encryptor mit expliziten Parametern. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte vom Referenztyp im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte vom Werttyp im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN nach IEC 60559:1989 mit keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN nach IEC 60559:1989 mit keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual void [GenerateIV](./generateiv/)() | Erzeugt einen zufälligen Initialwert für den Algorithmus. Überschreibt einen vorhandenen (falls vorhanden). |
| virtual void [GenerateKey](./generatekey/)() | Erzeugt einen zufälligen Schlüssel für den Algorithmus. Überschreibt einen vorhandenen (falls vorhanden). |
| virtual int [get_BlockSize](./get_blocksize/)() | Gibt die Blockgröße der kryptografischen Operation zurück. |
| virtual int [get_FeedbackSize](./get_feedbacksize/)() | Gibt die Rückkopplungsgröße der kryptografischen Operation zurück. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](./get_iv/)() | Gibt den Initialwert der kryptografischen Operation zurück. Erstellt einen neuen, falls noch keiner existiert. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](./get_key/)() | Gibt den Schlüssel der kryptografischen Operation zurück. Erstellt einen neuen, falls noch keiner existiert. |
| virtual int [get_KeySize](./get_keysize/)() | Gibt die Schlüssellänge der kryptografischen Operation zurück. |
| virtual [CipherMode](../ciphermode/) [get_Mode](./get_mode/)() | Gibt den Modus der kryptografischen Operation zurück. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](./get_padding/)() | Gibt das Padding der kryptografischen Operation zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Wertobjekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_BlockSize](./set_blocksize/)(int) | Setzt die Blockgröße der kryptografischen Operation. |
| virtual void [set_FeedbackSize](./set_feedbacksize/)(int) | Setzt die Rückkopplungsgröße der kryptografischen Operation. |
| virtual void [set_IV](./set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Setzt den Initialwert der kryptografischen Operation. |
| virtual void [set_Key](./set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Setzt den Schlüssel der kryptografischen Operation. |
| virtual void [set_KeySize](./set_keysize/)(int) | Setzt die Schlüssellänge der kryptografischen Operation. |
| virtual void [set_Mode](./set_mode/)([CipherMode](../ciphermode/)) | Setzt den Modus der kryptografischen Operation. |
| virtual void [set_Padding](./set_padding/)([PaddingMode](../paddingmode/)) | Setzt das Padding der kryptografischen Operation. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines gemeinsamen). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| **bool** [ValidKeySize](./validkeysize/)(int) | Prüft, ob die Schlüssellänge gültig ist. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Security::Cryptography](../)
* Bibliothek [Aspose.Slides](../../)