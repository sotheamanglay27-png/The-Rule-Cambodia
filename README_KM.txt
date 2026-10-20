ROS LOK Cambodia - Android project + cloud build

គម្រោងនេះដាក់ HTML របស់អ្នកក្នុង Android WebView។ ZIP នេះមិនទាន់មាន APK ដែល build រួចទេ។ វាមាន GitHub Actions workflow សម្រាប់ build APK នៅលើ cloud ដោយមិនចាំបាច់ប្រើកុំព្យូទ័រ។

របៀបប្រើតែទូរសព្ទ Android:
1. បង្កើត/ចូលគណនី GitHub នៅ github.com។
2. បង្កើត repository ថ្មី (ឧ. ros-lok-cambodia) ហើយជ្រើស Public ឬ Private តាមចិត្ត។
3. Upload ឯកសារនិងថតទាំងអស់ក្នុង ZIP នេះទៅ repository ដោយរក្សាទីតាំងថតដើម (រួមទាំង .github/workflows/build-apk.yml)។ វិធីងាយជាងគេគឺ extract ZIP លើទូរសព្ទ រួច upload files តាម browser ឬ GitHub app; ប្រសិនបើ upload តាម browser មិនអាច upload ថតទាំងមូលបាន ត្រូវបង្កើតថត/ឯកសារតាមទីតាំងត្រឹមត្រូវ។
4. បើក repository > Actions > Build ROS LOK Cambodia APK > Run workflow។ ប្រសិនបើវាមិនបង្ហាញ workflow ទេ ត្រូវ commit ឯកសារទៅ branch main ហើយ refresh។
5. ពេល workflow បញ្ចប់ដោយពណ៌បៃតង សូមបើក run នោះ ហើយទាញយក Artifact ឈ្មោះ ROS-LOK-Cambodia-debug-APK។
6. Extract ZIP ដែលបានទាញយក ហើយដំឡើង app-debug.apk។ Android អាចស្នើឱ្យអនុញ្ញាត Install unknown apps សម្រាប់ browser/files app ដែលប្រើទាញយក។ អនុញ្ញាតតែឯកសារដែលអ្នកទុកចិត្ត។

ព័ត៌មាន៖
- APK នេះជា debug APK សម្រាប់ដំឡើងសាកល្បង មិនមែន Play Store release ដែលបាន sign សម្រាប់ចែកចាយទេ។
- HTML ត្រូវបានដាក់ជាឯកសារក្នុង app; បណ្តាញអ៊ីនធឺណិតត្រូវការតែសម្រាប់មុខងារណាដែល HTML ខ្លួនវាត្រូវប្រើ online។
- សូមសាកល្បងលើទូរសព្ទ Android ពិត ដើម្បីពិនិត្យប៊ូតុង និងសំឡេង។
