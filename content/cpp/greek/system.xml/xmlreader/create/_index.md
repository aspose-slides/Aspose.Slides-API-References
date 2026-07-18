---
title: Create()
second_title: Aspose.Slides για την αναφορά API του C++
description: Δημιουργεί ένα νέο αντικείμενο XmlReader με το καθορισμένο URI.
type: docs
weight: 1015
url: /el/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο με το καθορισμένο URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Το URI για το αρχείο που περιέχει τα δεδομένα XML. Η [XmlUrlResolver](../../xmlurlresolver/) κλάση χρησιμοποιείται για τη μετατροπή της διαδρομής σε κανονική αναπαράσταση δεδομένων. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας το καθορισμένο URI και τις ρυθμίσεις.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Το URI για το αρχείο που περιέχει τα δεδομένα XML. Το αντικείμενο [XmlResolver](../../xmlresolver/) στο αντικείμενο [XmlReaderSettings](../../xmlreadersettings/) χρησιμοποιείται για τη μετατροπή της διαδρομής σε κανονική αναπαράσταση δεδομένων. Εάν η τιμή XmlReaderSettings::get_XmlResolver είναι **nullptr**, ένα νέο αντικείμενο [XmlUrlResolver](../../xmlurlresolver/) χρησιμοποιείται. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Οι ρυθμίσεις για το νέο [XmlReader](../) αντικείμενο. Η τιμή αυτή μπορεί να είναι **nullptr**. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας το καθορισμένο URI, τις ρυθμίσεις και τις πληροφορίες περιεχομένου για την ανάλυση.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Το URI για το αρχείο που περιέχει τα δεδομένα XML. Το αντικείμενο [XmlResolver](../../xmlresolver/) στο αντικείμενο [XmlReaderSettings](../../xmlreadersettings/) χρησιμοποιείται για τη μετατροπή της διαδρομής σε κανονική αναπαράσταση δεδομένων. Εάν η τιμή XmlReaderSettings::get_XmlResolver είναι **nullptr**, ένα νέο αντικείμενο [XmlUrlResolver](../../xmlurlresolver/) χρησιμοποιείται. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Οι ρυθμίσεις για το νέο [XmlReader](../) αντικείμενο. Η τιμή αυτή μπορεί να είναι **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Οι πληροφορίες περιεχομένου που απαιτούνται για την ανάλυση του τμήματος XML. Οι πληροφορίες περιεχομένου μπορεί να περιλαμβάνουν το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί, κωδικοποίηση, εμβέλεια ονοματοχώρου, την τρέχουσα εμβέλεια **xml:lang** και **xml:space**, το βασικό URI και τον ορισμό τύπου εγγράφου. Η τιμή αυτή μπορεί να είναι **nullptr**. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας τη καθορισμένη ροή με προεπιλεγμένες ρυθμίσεις.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει τα δεδομένα XML. Ο [XmlReader](../) σαρώει τα πρώτα byte της ροής αναζητώντας ένα byte order mark ή κάποιο άλλο σημάδι κωδικοποίησης. Όταν η κωδικοποίηση καθοριστεί, χρησιμοποιείται για τη συνέχιση της ανάγνωσης της ροής, και η επεξεργασία συνεχίζει την ανάλυση της εισόδου ως ροή χαρακτήρων (Unicode). |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο με τη καθορισμένη ροή και τις ρυθμίσεις.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει τα δεδομένα XML. Ο [XmlReader](../) σαρώει τα πρώτα byte της ροής αναζητώντας ένα byte order mark ή κάποιο άλλο σημάδι κωδικοποίησης. Όταν η κωδικοποίηση καθοριστεί, χρησιμοποιείται για τη συνέχιση της ανάγνωσης της ροής, και η επεξεργασία συνεχίζει την ανάλυση της εισόδου ως ροή χαρακτήρων (Unicode). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Οι ρυθμίσεις για το νέο [XmlReader](../) αντικείμενο. Η τιμή αυτή μπορεί να είναι **nullptr**. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας τη καθορισμένη ροή, το βασικό URI και τις ρυθμίσεις.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει τα δεδομένα XML. Ο [XmlReader](../) σαρώει τα πρώτα byte της ροής αναζητώντας ένα byte order mark ή κάποιο άλλο σημάδι κωδικοποίησης. Όταν η κωδικοποίηση καθοριστεί, χρησιμοποιείται για τη συνέχιση της ανάγνωσης της ροής, και η επεξεργασία συνεχίζει την ανάλυση της εισόδου ως ροή χαρακτήρων (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Οι ρυθμίσεις για το νέο [XmlReader](../) αντικείμενο. Η τιμή αυτή μπορεί να είναι **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Το βασικό URI για την οντότητα ή το έγγραφο που διαβάζεται. Η τιμή αυτή μπορεί να είναι **nullptr**. **[Security](../../../system.security/) Σημείωση** Το βασικό URI χρησιμοποιείται για την επίλυση του σχετικού URI του εγγράφου XML. Μην χρησιμοποιείτε ένα βασικό URI από μη αξιόπιστη πηγή. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας τη καθορισμένη ροή, τις ρυθμίσεις και τις πληροφορίες περιεχομένου για την ανάλυση.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει τα δεδομένα XML. Ο [XmlReader](../) σαρώει τα πρώτα byte της ροής αναζητώντας ένα byte order mark ή κάποιο άλλο σημάδι κωδικοποίησης. Όταν η κωδικοποίηση καθοριστεί, χρησιμοποιείται για τη συνέχιση της ανάγνωσης της ροής, και η επεξεργασία συνεχίζει την ανάλυση της εισόδου ως ροή χαρακτήρων (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Οι ρυθμίσεις για το νέο [XmlReader](../) αντικείμενο. Η τιμή αυτή μπορεί να είναι **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Οι πληροφορίες περιεχομένου που απαιτούνται για την ανάλυση του τμήματος XML. Οι πληροφορίες περιεχομένου μπορεί να περιλαμβάνουν το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί, κωδικοποίηση, εμβέλεια ονοματοχώρου, την τρέχουσα εμβέλεια **xml:lang** και **xml:space**, το βασικό URI και τον ορισμό τύπου εγγράφου. Η τιμή αυτή μπορεί να είναι **nullptr**. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Ο αναγνώστης κειμένου από τον οποίο διαβάζονται τα δεδομένα XML. Ένας αναγνώστης κειμένου επιστρέφει μια ροή χαρακτήρων Unicode, επομένως η κωδικοποίηση που καθορίζεται στη δήλωση XML δεν χρησιμοποιείται από τον αναγνώστη XML για την αποκωδικοποίηση της ροής δεδομένων. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου και τις ρυθμίσεις.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Ο αναγνώστης κειμένου από τον οποίο διαβάζονται τα δεδομένα XML. Ένας αναγνώστης κειμένου επιστρέφει μια ροή χαρακτήρων Unicode, επομένως η κωδικοποίηση που καθορίζεται στη δήλωση XML δεν χρησιμοποιείται από τον αναγνώστη XML για την αποκωδικοποίηση της ροής δεδομένων. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Οι ρυθμίσεις για το νέο [XmlReader](../). Η τιμή αυτή μπορεί να είναι **nullptr**. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου, τις ρυθμίσεις και το βασικό URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Ο αναγνώστης κειμένου από τον οποίο διαβάζονται τα δεδομένα XML. Ένας αναγνώστης κειμένου επιστρέφει μια ροή χαρακτήρων Unicode, επομένως η κωδικοποίηση που καθορίζεται στη δήλωση XML δεν χρησιμοποιείται από το [XmlReader](../) για την αποκωδικοποίηση της ροής δεδομένων. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Οι ρυθμίσεις για το νέο [XmlReader](../) αντικείμενο. Η τιμή αυτή μπορεί να είναι **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Το βασικό URI για την οντότητα ή το έγγραφο που διαβάζεται. Η τιμή αυτή μπορεί να είναι **nullptr**. **[Security](../../../system.security/) Σημείωση** Το βασικό URI χρησιμοποιείται για την επίλυση του σχετικού URI του εγγράφου XML. Μην χρησιμοποιείτε ένα βασικό URI από μη αξιόπιστη πηγή. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας τον καθορισμένο αναγνώστη κειμένου, τις ρυθμίσεις και τις πληροφορίες περιεχομένου για την ανάλυση.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Ο αναγνώστης κειμένου από τον οποίο διαβάζονται τα δεδομένα XML. Ένας αναγνώστης κειμένου επιστρέφει μια ροή χαρακτήρων Unicode, επομένως η κωδικοποίηση που καθορίζεται στη δήλωση XML δεν χρησιμοποιείται από τον αναγνώστη XML για την αποκωδικοποίηση της ροής δεδομένων. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Οι ρυθμίσεις για το νέο [XmlReader](../) αντικείμενο. Η τιμή αυτή μπορεί να είναι **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Οι πληροφορίες περιεχομένου που απαιτούνται για την ανάλυση του τμήματος XML. Οι πληροφορίες περιεχομένου μπορεί να περιλαμβάνουν το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί, κωδικοποίηση, εμβέλεια ονοματοχώρου, την τρέχουσα εμβέλεια **xml:lang** και **xml:space**, το βασικό URI και τον ορισμό τύπου εγγράφου. Η τιμή αυτή μπορεί να είναι **nullptr**. |

### Τιμή Επιστροφής

Ένα αντικείμενο που χρησιμοποιείται για την ανάγνωση των δεδομένων XML στη ροή.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) μέθοδος

Δημιουργεί ένα νέο [XmlReader](../) αντικείμενο χρησιμοποιώντας τον καθορισμένο αναγνώστη XML και τις ρυθμίσεις.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Το αντικείμενο που θέλετε να χρησιμοποιήσετε ως βασικό αναγνώστη XML. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Οι ρυθμίσεις για το νέο [XmlReader](../) αντικείμενο. Το επίπεδο συμμόρφωσης του αντικειμένου [XmlReaderSettings](../../xmlreadersettings/) πρέπει είτε να ταιριάζει με το επίπεδο συμμόρφωσης του υποκείμενου αναγνώστη, είτε να ορίζεται σε [ConformanceLevel::Auto](../../conformancelevel/). |

### Τιμή Επιστροφής

Ένα αντικείμενο που είναι τυλιγμένο γύρω από το καθορισμένο αντικείμενο [XmlReader](../).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)