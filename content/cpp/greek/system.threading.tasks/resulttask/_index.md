---
title: ResultTask
second_title: Aspose.Slides για C++ Αναφορά API
description: Μια εξειδίκευση Task που επιστρέφει μια τιμή αποτελέσματος κατά την ολοκλήρωση.
type: docs
weight: 40
url: /el/system.threading.tasks/resulttask/
---
## Κλάση ResultTask

Μια [Task](../task/) εξειδίκευση που επιστρέφει μια τιμή αποτελέσματος κατά την ολοκλήρωση.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of the result value returned by the task |
## Μέθοδοι

| Method | Description |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Ενεργοποιεί την εργασία για εκτέλεση σε έναν προγραμματιστή. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Προσθέτει μια ενέργεια συνέχειας που θα εκτελεστεί κατά την ολοκλήρωση. |
| void [Cancel](../task/cancel/)() | Σημειώνει την εργασία ως ακυρωμένη και τερματίζει την εργασία. |
| void [Complete](./complete/)(const T\&) | Ορίζει την τιμή αποτελέσματος για την εργασία και την ολοκληρώνει. |
| void [Complete](../task/complete/)() | Σημειώνει την εργασία ως ολοκληρωμένη και τερματίζει την εργασία. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Διαμορφώνει πώς οι αναμονές σε αυτήν την εργασία αποτελέσματος πρέπει να συμπεριφέρονται ως προς τη σύλληψη του περιβάλλοντος. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Δημιουργεί μια συνέχιση που εκτελείται όταν η εργασία αποτελέσματος ολοκληρώνεται. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Δημιουργεί μια συνέχιση που εκτελείται όταν η εργασία αποτελέσματος ολοκληρώνεται. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Δημιουργεί μια συνέχιση που εκτελείται όταν η εργασία ολοκληρώνεται. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Δημιουργεί μια συνέχιση που εκτελείται όταν η εργασία ολοκληρώνεται. |
| void [Deactivate](../task/deactivate/)() | Απενεργοποιεί την εργασία για εκτέλεση στον τρέχον προγραμματιστή της, εφόσον υπάρχει. |
| void [Dispose](../task/dispose/)() override | Απελευθερώνει τους πόρους που σχετίζονται με την εργασία. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| void [Execute](../task/execute/)() | Εκτελεί τη συνάρτηση της εργασίας. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Παίρνει το αντικείμενο κατάστασης ορισμένο από τον χρήστη που σχετίζεται με την εργασία. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Παίρνει μια ολοκληρωμένη εργασία (μονότυπο) |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Παίρνει το ID για την εργασία. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Παίρνει αν η εργασία ολοκληρώθηκε λόγω ακύρωσης. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Παίρνει αν η εργασία έχει ολοκληρωθεί. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Παίρνει αν η εργασία ολοκληρώθηκε λόγω μη διαχειρισμένης εξαίρεσης. |
| T [get_Result](./get_result/)() | Παίρνει το αποτέλεσμα της ασύγχρονης λειτουργίας. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Παίρνει τον προγραμματιστή που σχετίζεται με αυτήν την εργασία. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Παίρνει την τρέχουσα κατάσταση της εργασίας. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Παίρνει έναν awaiter για αυτήν την εργασία αποτελέσματος για χρήση με Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια έκδοση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τον μηχανισμό κλειδώματος της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών με αντιγραφή. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών με αντιγραφή. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Δομεί ένα [ResultTask](./) με μια συνάρτηση που επιστρέφει μια τιμή. |
|  [ResultTask](./resulttask/)() | Εσωτερική υλοποίηση. Δεν προορίζεται για κώδικα χρήστη. |
|  [ResultTask](./resulttask/)(const T\&) | Εσωτερικός κατασκευαστής για δημιουργία εργασιών αποτελέσματος με καθορισμένο αποτέλεσμα. |
| void [RunSynchronously](../task/runsynchronously/)() | Εκτελεί την εργασία συγχρόνως στο τρέχον νήμα. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Εκτελεί την εργασία συγχρόνως χρησιμοποιώντας τον καθορισμένο προγραμματιστή. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Ορίζει την εσωτερική συνάρτηση προς εκτέλεση. |
| void [set_Result](./set_result/)(const T\&) | Ορίζει την τιμή αποτελέσματος για την εργασία. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Ορίζει τον προγραμματιστή που σχετίζεται με αυτήν την εργασία. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Ορίζει την κατάσταση της εργασίας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th (n-οστό) όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόδεικτη). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [Start](../task/start/)() | Ξεκινά την εκτέλεση της εργασίας χρησιμοποιώντας τον προεπιλεγμένο προγραμματιστή. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Ξεκινά την εκτέλεση της εργασίας χρησιμοποιώντας τον καθορισμένο προγραμματιστή. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Δομεί ένα [Task](../task/) με μια ενέργεια προς εκτέλεση. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Δομεί ένα [Task](../task/) με μια ενέργεια και διακριτικό ακύρωσης. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Δομεί ένα [Task](../task/) με μια καταστάσιμη ενέργεια και αντικείμενο κατάστασης. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Δομεί ένα [Task](../task/) με καταστάσιμη ενέργεια, κατάσταση και διακριτικό ακύρωσης. |
|  [Task](../task/task/)() | Εσωτερικός κατασκευαστής για δημιουργία μη αρχικοποιημένων εργασιών. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Περιμένει την ολοκλήρωση της εργασίας με υποστήριξη ακύρωσης. |
| void [Wait](../task/wait/)() | Περιμένει την ολοκλήρωση της εργασίας. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |
|  [~Task](../task/~task/)() | Καταστροφέας. |
## Παρατηρήσεις

Αναπαριστά μια ασύγχρονη λειτουργία που παράγει ένα αποτέλεσμα, παρόμοια με το System.Threading.Tasks.Task<TResult> στο .NET 
## Δείτε επίσης

* Κλάση [Task](../task/)
* Ονοματοχώρος [System::Threading::Tasks](../)
* Βιβλιοθήκη [Aspose.Slides](../../)