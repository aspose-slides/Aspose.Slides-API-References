---
title: IDocumentProperties
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Eigenschaften einer Präsentation dar.
type: docs
weight: 1977
url: /de/aspose.slides/idocumentproperties/
---
## IDocumentProperties Klasse

Stellt die Eigenschaften einer Präsentation dar.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Löscht und setzt Standardwerte für alle builtIn Eigenschaften. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Entfernt alle benutzerdefinierten Eigenschaften. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung von C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Fließkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Fließkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Gibt die Vorlage einer Anwendung zurück. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Gibt die Anwendungs-Version zurück. Nur lesend [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Gibt den Autor einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Gibt die Kategorie einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Gibt die Kommentare einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Gibt die Unternehmens-Eigenschaft zurück. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Gibt den Inhaltsstatus einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Gibt den Inhaltstyp einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Gibt die tatsächliche Anzahl benutzerdefinierter Eigenschaften in einer Sammlung zurück. Nur lesend **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lesen [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Zeigt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Nur lesend [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Gibt die Anzahl versteckter Folien in einem Präsentationsdokument an. Nur lesend **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Gibt die Dokument-Eigenschaft HyperlinkBase zurück. Lesen [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lesen **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Gibt die Schlüsselwörter einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lesen [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Gibt den Namen der letzten Person zurück, die eine Präsentation bearbeitet hat. Lesen [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Setzt das Datum, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Schreiben-nur im Fall von Presentation.DocumentProperties (weil es intern während des [IPresentation](../ipresentation/) Objekt-Speicherprozesses aktualisiert wird). Kann über die von Methode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) zurückgegebene [DocumentProperties](../documentproperties/)-Instanz geändert werden. Siehe das Beispiel in der Zusammenfassung der Methode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lesen **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Gibt die Manager-Eigenschaft zurück. Lesen [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Gibt die Gesamtzahl von Ton- oder Video-Clips im Dokument an. Nur lesend **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Gibt den Namen der Anwendung zurück. Lesen [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Gibt die Anzahl der Folien in einer Präsentation mit Notizen an. Nur lesend **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Gibt die Gesamtzahl der im Dokument gefundenen Absätze an, falls zutreffend. Nur lesend **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Gibt das beabsichtigte Format einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Gibt die Revisionsnummer der Präsentation zurück. Lesen **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Gibt den Anzeigemodus der Dokument-Miniatur an. Setzen Sie dieses Element auf **true**, um das Skalieren der Dokument-Miniatur an die Anzeige zu ermöglichen. Setzen Sie dieses Element auf **false**, um das Zuschneiden der Dokument-Miniatur so zu ermöglichen, dass nur Abschnitte angezeigt werden, die zur Anzeige passen. Lesen **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lesen **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument an. Nur lesend **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Gibt den Betreff einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Gibt den Titel einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptuelle Darstellungen von Dokumentabschnitten. Nur lesend [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Gesamte Bearbeitungszeit einer Präsentation. Lesen [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Gibt die Gesamtzahl der im Dokument enthaltenen Wörter an. Nur lesend **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Gibt einen benutzerdefinierten Eigenschaftsnamen am angegebenen Index zurück. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Ermittelt einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Ermittelt einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Ermittelt einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Ermittelt einen benannten Zeichenkettenwert aus den benutzerdefinierten Eigenschaften. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Ermittelt einen benannten float-Wert aus den benutzerdefinierten Eigenschaften. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Ermittelt einen benannten double-Wert aus den benutzerdefinierten Eigenschaften. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Erhält ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück. Lesen [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Setzt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft. Schreiben [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Entfernt eine mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Setzt die Vorlage einer Anwendung. Schreiben [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Setzt den Autor einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Setzt die Kategorie einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Setzt die Kommentare einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Setzt die Unternehmens-Eigenschaft. Schreiben [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Setzt den Inhaltsstatus einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Setzt den Inhaltstyp einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Setzt das Erstellungsdatum einer Präsentation. Werte sind in UTC. Schreiben [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Setzt die Dokument-Eigenschaft HyperlinkBase. Schreiben [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Schreiben **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Setzt die Schlüsselwörter einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Setzt das Datum, an dem eine Präsentation zuletzt gedruckt wurde. Schreiben [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Setzt den Namen der letzten Person, die eine Präsentation bearbeitet hat. Schreiben [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Setzt das Datum, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Schreiben-nur im Fall von Presentation.DocumentProperties (weil es intern während des [IPresentation](../ipresentation/) Objekt-Speicherprozesses aktualisiert wird). Kann über die von Methode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) zurückgegebene [DocumentProperties](../documentproperties/)-Instanz geändert werden. Siehe das Beispiel in der Zusammenfassung der Methode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Schreiben **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Setzt die Manager-Eigenschaft. Schreiben [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Setzt den Namen der Anwendung. Schreiben [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Setzt das beabsichtigte Format einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Setzt die Revisionsnummer der Präsentation. Schreiben **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Gibt den Anzeigemodus der Dokument-Miniatur an. Setzen Sie dieses Element auf **true**, um das Skalieren der Dokument-Miniatur an die Anzeige zu ermöglichen. Setzen Sie dieses Element auf **false**, um das Zuschneiden der Dokument-Miniatur so zu ermöglichen, dass nur Abschnitte angezeigt werden, die zur Anzeige passen. Schreiben **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Schreiben **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Setzt den Betreff einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Setzt den Titel einer Präsentation. Schreiben [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Gesamte Bearbeitungszeit einer Präsentation. Schreiben [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Setzt eine benannte Zeichenketten-benutzerdefinierte Eigenschaft. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Setzt eine benannte float-benutzerdefinierte Eigenschaft. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Setzt eine benannte double-benutzerdefinierte Eigenschaft. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines gemeinsam genutzten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)