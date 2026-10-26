---
title: "System::Threading::Tasks"
second_title: Αναφορά API του Aspose.Slides για C++
description: 
type: docs
weight: 1015
url: /el/system.threading.tasks/
---
## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [Parallel](./parallel/) | Παρέχει υποστήριξη για παράλληλες βρόχους και περιοχές. |
| [ParallelLoopResult](./parallelloopresult/) | Παρέχει την κατάσταση ολοκλήρωσης ενός βρόχου [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | Αποθηκεύει επιλογές που διαμορφώνουν τη λειτουργία των μεθόδων στην κλάση [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Μια εξειδίκευση [Task](./task/) που επιστρέφει μια τιμή αποτελέσματος μετά την ολοκλήρωση. |
| [ResultValueTask](./resultvaluetask/) | Αντιπροσωπεύει έναν υβριδικό τύπο τύπου task που μπορεί να περιβάλλει είτε μια άμεση τιμή αποτελέσματος είτε ένα ResultTask<T>. |
| [Task](./task/) | Αντιπροσωπεύει μια ασύγχρονη λειτουργία που μπορεί να περιμετρηθεί και να συντεθεί με άλλες εργασίες. |
| [TaskScheduler](./taskscheduler/) | Αντιπροσωπεύει ένα αντικείμενο που διαχειρίζεται τη χαμηλού επιπέδου εργασία της τοποθέτησης εργασιών σε νήματα. |
| [ValueTask](./valuetask/) | Παρέχει ένα αποτελέσμα που μπορεί να περιμετρηθεί μιας ασύγχρονης λειτουργίας. |

## Συναρτήσεις

| Συνάρτηση | Περιγραφή |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Δημιουργεί μια εργασία που ολοκληρώνεται μετά από καθυστέρηση χρόνου. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Δημιουργεί μια εργασία που ολοκληρώνεται μετά από καθυστέρηση χρόνου και μπορεί να ακυρωθεί. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Δημιουργεί μια εργασία που έχει ολοκληρωθεί λόγω ακύρωσης με το καθορισμένο διακριτικό. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Δημιουργεί μια εργασία που έχει ολοκληρωθεί με μια καθορισμένη εξαίρεση. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Δημιουργεί μια εργασία που έχει ολοκληρωθεί με μια καθορισμένη εξαίρεση και τύπο αποτελέσματος. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Δημιουργεί μια εργασία που ολοκληρώθηκε επιτυχώς με το καθορισμένο αποτέλεσμα. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Τοποθετεί το καθορισμένο έργο στην ουρά για εκτέλεση στην ομάδα νήματος και επιστρέφει έναν χειριστή [Task](./task/) για αυτήν την εργασία. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Τοποθετεί το καθορισμένο έργο στην ουρά για εκτέλεση στην ομάδα νήματος και επιστρέφει έναν χειριστή [Task](./task/) για αυτήν την εργασία. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Τοποθετεί το καθορισμένο έργο στην ουρά για εκτέλεση στην ομάδα νήματος και επιστρέφει έναν διαμεσολαβητή για το [Task](./task/) που επιστρέφεται από τη συνάρτηση. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Τοποθετεί το καθορισμένο έργο στην ουρά για εκτέλεση στην ομάδα νήματος και επιστρέφει έναν χειριστή Task<TResult> για αυτήν την εργασία. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Περιμένει να ολοκληρωθεί η εκτέλεση όλων των παρεχόμενων αντικειμένων [Task](./task/). |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Περιμένει να ολοκληρωθεί η εκτέλεση όλων των παρεχόμενων αντικειμένων [Task](./task/). |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Περιμένει να ολοκληρωθεί η εκτέλεση οποιουδήποτε από τα παρεχόμενα αντικείμενα [Task](./task/). |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Περιμένει να ολοκληρωθεί η εκτέλεση οποιουδήποτε από τα παρεχόμενα αντικείμενα [Task](./task/). |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθούν όλες οι παρεχόμενες εργασίες. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Δημιουργεί μια εργασία που θα ολοκληρωθεί όταν ολοκληρωθεί οποιαδήποτε από τις παρεχόμενες εργασίες. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Δημιουργεί μια εργασία που μπορεί να περιμετρηθεί και που επιστρέφει ασύγχρονα στο τρέχον πλαίσιο όταν περιμετρηθεί. |

## Απαριθμός

| Απαριθμός | Περιγραφή |
| --- | --- |
| [TaskStatus](./taskstatus/) |  