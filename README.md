# Test Module

###### testImplementation "com.github.x-syaifullah-x.android-test:test:$vAndroidModulTest"
###### androidTestImplementation "com.github.x-syaifullah-x.android-test:test:$vAndroidModulTest"
###### testImplementation "com.github.x-syaifullah-x.android-test:test_navigation:$vAndroidModulTest"
###### androidTestImplementation("com.github.x-syaifullah-x.android-module-test:test_navigation:$vAndroidModulTest") {
######           androidTestImplementation "androidx.fragment:fragment-ktx:$versions"
######       }

       run test error More than one file was found with OS independent path '.....'
                packagingOptions {
                    exclude "**/attach_hotspot_windows.dll"
                    exclude "META-INF/licenses/ASM"
                    exclude "META-INF/AL2.0"
                    exclude "META-INF/LGPL2.1"
                }
