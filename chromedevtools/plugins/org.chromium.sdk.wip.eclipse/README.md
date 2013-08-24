

### Maven build note

Require-Bundle: org.chromium.sdk.feature;bundle-version="0.3.9"
still can't find 

[ERROR] Internal error: java.lang.RuntimeException: "No solution found because the problem is unsatisfiable.": ["Unable to satisfy dependency from org.chromium.
sdk.wip.eclipse 0.3.9.qualifier to bundle org.chromium.sdk.feature 0.3.9.", "No solution found because the problem is unsatisfiable."] -> [Help 1]
org.apache.maven.InternalErrorException: Internal error: java.lang.RuntimeException: "No solution found because the problem is unsatisfiable.": ["Unable to sati
sfy dependency from org.chromium.sdk.wip.eclipse 0.3.9.qualifier to bundle org.chromium.sdk.feature 0.3.9.", "No solution found because the problem is unsatisfi
able."]

so return back to 

Require-Bundle: org.chromium.sdk;bundle-version="0.3.9"
