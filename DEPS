# Showcases a gclient sync race condition with neseted DEPS.

# Avoids the need for a custom root variable.
use_relative_paths = True
use_relative_hooks = True

vars = {
  'chromium_git': 'https://chromium.googlesource.com',
}

deps = {
 
  'third_party/jsoncpp': {
    'url': '{chromium_git}/chromium/src/third_party/jsoncpp@48246a099549ab325c01f69f24a34fc72e5c42e4',
   },

  'third_party/jsoncpp/source': {
    'url' : '{chromium_git}/external/github.com/open-source-parsers/jsoncpp.git@645250b6690785be60ab6780ce4b58698d884d11',
   },


  'third_party/yasm': {
    'url': '{chromium_git}/chromium/src/third_party/yasm@cc10bc0f1d96a4bae0e775f2ac2b6ac5b08078c6',
  },

  'third_party/yasm/source/patched-yasm': {
    'url': '{chromium_git}/chromium/deps/yasm/patched-yasm.git@720b70524a4424b15fc57e82263568c8ba0496ad',
  },

}
