# Changelog

## [2.4.1](https://github.com/stevearc/oil.nvim/compare/v2.4.0...v2.4.1) (2023-12-01)


### Bug Fixes

* buffer data cleared when setting buflisted = false ([303f318](https://github.com/stevearc/oil.nvim/commit/303f31895e7ce10df250c88c7a5f7d8d9c56f0fc))
* bug copying file multiple times ([05cb825](https://github.com/stevearc/oil.nvim/commit/05cb8257cb9257144e63f41ccfe5a41ba3d1003c))
* crash in ssh and trash adapter detail columns ([#235](https://github.com/stevearc/oil.nvim/issues/235)) ([e89a8f8](https://github.com/stevearc/oil.nvim/commit/e89a8f8adeef2dfab851fd056d38ee7afc97c249))
* oil.select respects splitbelow and splitright ([#233](https://github.com/stevearc/oil.nvim/issues/233)) ([636989b](https://github.com/stevearc/oil.nvim/commit/636989b603fb95032efa9d3e1b3323c8bb533e91))
* preserve buflisted when re-opening oil buffers ([#220](https://github.com/stevearc/oil.nvim/issues/220)) ([6566f45](https://github.com/stevearc/oil.nvim/commit/6566f457e44498adc6835bed5402b38386fa1438))

## [2.4.0](https://github.com/stevearc/oil.nvim/compare/v2.3.0...v2.4.0) (2023-11-15)


### Features

* display ../ entry in oil buffers ([#166](https://github.com/stevearc/oil.nvim/issues/166)) ([d8f0d91](https://github.com/stevearc/oil.nvim/commit/d8f0d91b10ec53da722b0909697b57c2f5368245))
* trash support for linux and mac ([#165](https://github.com/stevearc/oil.nvim/issues/165)) ([6175bd6](https://github.com/stevearc/oil.nvim/commit/6175bd646272335c8db93264760760d8f2a611d5))


### Bug Fixes

* can view drives on Windows ([126a8a2](https://github.com/stevearc/oil.nvim/commit/126a8a23465312683edf646555b3031bfe56796d))
* don't set buflisted on oil buffers ([#220](https://github.com/stevearc/oil.nvim/issues/220)) ([873d505](https://github.com/stevearc/oil.nvim/commit/873d505e5bfdd65317ea97ead8faa6c56bac04c0))
* line parsing for empty columns ([0715f1b](https://github.com/stevearc/oil.nvim/commit/0715f1b0aacef70573ed6300c12039831fbd81c3))
* previewing and editing files on windows ([#214](https://github.com/stevearc/oil.nvim/issues/214)) ([3727410](https://github.com/stevearc/oil.nvim/commit/3727410e4875ad8ba339c585859a9391d643b9ed))
* quit after mutations when :wq or similar ([#221](https://github.com/stevearc/oil.nvim/issues/221)) ([af13ce3](https://github.com/stevearc/oil.nvim/commit/af13ce333f89c54a47e6772b55fed2438ee6957c))

## [2.3.0](https://github.com/stevearc/oil.nvim/compare/v2.2.0...v2.3.0) (2023-11-04)


### Features

* add support for LSP willRenameFiles ([#184](https://github.com/stevearc/oil.nvim/issues/184)) ([8f3c1d2](https://github.com/stevearc/oil.nvim/commit/8f3c1d2d2e4f7b81d19f353c61cb4ccba6a26496))
* make buffer cleanup delay configurable ([#191](https://github.com/stevearc/oil.nvim/issues/191)) ([a9f7f69](https://github.com/stevearc/oil.nvim/commit/a9f7f6927de2ceab01c9dfddd5a0d96330fe6374))


### Bug Fixes

* call vimL function in main loop ([#206](https://github.com/stevearc/oil.nvim/issues/206)) ([8418e94](https://github.com/stevearc/oil.nvim/commit/8418e94734e2572b422aead6e28d5a4c5b543d1f))
* case handling for LSP willRenameFiles ([deba4db](https://github.com/stevearc/oil.nvim/commit/deba4db1aca6e3970c94499401da001694d01138))
* disable swapfile for oil buffers ([#190](https://github.com/stevearc/oil.nvim/issues/190)) ([2e6996b](https://github.com/stevearc/oil.nvim/commit/2e6996b0757c454a8bbf1eb719d0b0b065442213))
* more correct gf binding for ssh files ([1641357](https://github.com/stevearc/oil.nvim/commit/164135793d893efad9ed6f90ac74a1ab54c4182a))
* parse errors when moving files across adapters ([4088efb](https://github.com/stevearc/oil.nvim/commit/4088efb8ff664b6f1624aab5dac6c3fe11d3962c))
* path shortening does proper subpath detection ([054247b](https://github.com/stevearc/oil.nvim/commit/054247b9c1799edd5874231973db621553062a43))
* restore original window when closing floating win ([#208](https://github.com/stevearc/oil.nvim/issues/208)) ([aea896a](https://github.com/stevearc/oil.nvim/commit/aea896a880e294c97a7c395dd8a6c89bdc93c644))
* shorten path when opening files ([#194](https://github.com/stevearc/oil.nvim/issues/194), [#197](https://github.com/stevearc/oil.nvim/issues/197)) ([3275996](https://github.com/stevearc/oil.nvim/commit/3275996ce65f142d0e96b9fc2658f94e5bd43ad5))
* shorten path when opening files ([#194](https://github.com/stevearc/oil.nvim/issues/194)) ([6cbc8d7](https://github.com/stevearc/oil.nvim/commit/6cbc8d725d3964cb08d679774db67d41fa002647))

## [2.2.0](https://github.com/stevearc/oil.nvim/compare/v2.1.0...v2.2.0) (2023-09-30)


### Features

* action for opening entry in an external program ([#183](https://github.com/stevearc/oil.nvim/issues/183)) ([96a334a](https://github.com/stevearc/oil.nvim/commit/96a334abeb85a26af87585ec3810116c7cb7d172))
* keymaps can specify mode ([#187](https://github.com/stevearc/oil.nvim/issues/187)) ([977da9a](https://github.com/stevearc/oil.nvim/commit/977da9ac6655b4f52bc26f23f584d9553f419555))
* make gf work in ssh files ([#186](https://github.com/stevearc/oil.nvim/issues/186)) ([ee81363](https://github.com/stevearc/oil.nvim/commit/ee813638d2d042e4b8e6e8ffd00dae438bdbd4ca))


### Bug Fixes

* add busybox support for ssh adapter ([#173](https://github.com/stevearc/oil.nvim/issues/173)) ([a9ceb90](https://github.com/stevearc/oil.nvim/commit/a9ceb90a63955c409b6fbac0f5cfc4c2f43093fd))
* correctly resolve new files when selected ([#179](https://github.com/stevearc/oil.nvim/issues/179)) ([83e4d04](https://github.com/stevearc/oil.nvim/commit/83e4d049228233df1870c92e160effb33e314396))
* don't override FloatTitle highlight ([#189](https://github.com/stevearc/oil.nvim/issues/189)) ([5ced687](https://github.com/stevearc/oil.nvim/commit/5ced687ddd08e1f8df27a23884d516a9b24101fc))
* hide swapfile error when editing file ([#188](https://github.com/stevearc/oil.nvim/issues/188)) ([bfc5a4c](https://github.com/stevearc/oil.nvim/commit/bfc5a4c48f4a53b95648e41d91e49b83fb03e919))

## [2.1.0](https://github.com/stevearc/oil.nvim/compare/v2.0.1...v2.1.0) (2023-09-11)


### Features

* api to sort directory contents ([#169](https://github.com/stevearc/oil.nvim/issues/169)) ([879d280](https://github.com/stevearc/oil.nvim/commit/879d280617045d5a00d7a053e86d51c6c80970be))


### Bug Fixes

* allow converting a file to directory and vice-versa ([#117](https://github.com/stevearc/oil.nvim/issues/117)) ([926ae06](https://github.com/stevearc/oil.nvim/commit/926ae067eb9a79817a455d5ab2dc6f420beb53c0))
* change default winblend for floating window to 0 ([#167](https://github.com/stevearc/oil.nvim/issues/167)) ([7033d52](https://github.com/stevearc/oil.nvim/commit/7033d52db012666b85504fe9a678939e49bc14b7))
* lock cursor to first mutable column ([d4eb4f3](https://github.com/stevearc/oil.nvim/commit/d4eb4f3bbf7770d04070707c947655a5426d7f75))

## [2.0.1](https://github.com/stevearc/oil.nvim/compare/v2.0.0...v2.0.1) (2023-08-26)


### Bug Fixes

* data loss bug when move + delete ([#162](https://github.com/stevearc/oil.nvim/issues/162)) ([f86d494](https://github.com/stevearc/oil.nvim/commit/f86d49446ae344ba3762d5705505aa09c1c1d4ee))

## [2.0.0](https://github.com/stevearc/oil.nvim/compare/v1.1.0...v2.0.0) (2023-08-24)


### ⚠ BREAKING CHANGES

* disable netrw by default ([#155](https://github.com/stevearc/oil.nvim/issues/155))

### Bug Fixes

* actions.terminal supports ssh adapter ([#152](https://github.com/stevearc/oil.nvim/issues/152)) ([0ccf95a](https://github.com/stevearc/oil.nvim/commit/0ccf95ae5d0ea731de8d427304f95d384a0664c4))
* errors when writing files over ssh ([#159](https://github.com/stevearc/oil.nvim/issues/159)) ([bfa0e87](https://github.com/stevearc/oil.nvim/commit/bfa0e8705eb83a0724aed6d5dc9d21aa62a8986b))
* fix flaky test ([9509ae0](https://github.com/stevearc/oil.nvim/commit/9509ae0feed5af04e4652375740a0722f2ee1a64))
* remaining type errors ([8f78079](https://github.com/stevearc/oil.nvim/commit/8f7807946a67b5f1a515946f82251e33651bae29))
* set nomodifiable after BufWritePre in ssh adapter ([#159](https://github.com/stevearc/oil.nvim/issues/159)) ([b61bc9b](https://github.com/stevearc/oil.nvim/commit/b61bc9b701a3cfb05cb6668446b0303cda7435e6))
* sometimes use shell to run trash command ([#99](https://github.com/stevearc/oil.nvim/issues/99)) ([ff62fc2](https://github.com/stevearc/oil.nvim/commit/ff62fc28cd7976e49ddff6897a4f870785187f13))
* ssh adapter supports any system with /bin/sh ([#161](https://github.com/stevearc/oil.nvim/issues/161)) ([ebcd720](https://github.com/stevearc/oil.nvim/commit/ebcd720a0987ed39f943c4a5d32b96d42e9cf695))
* type annotations and type errors ([47c7737](https://github.com/stevearc/oil.nvim/commit/47c77376189e4063b4fcc6dc2c4cfe8ffd72c782))


### Performance Improvements

* tweak uv readdir params for performance ([ffb89bf](https://github.com/stevearc/oil.nvim/commit/ffb89bf416a4883cc12e5ed247885d4700b00a0f))


### Code Refactoring

* disable netrw by default ([#155](https://github.com/stevearc/oil.nvim/issues/155)) ([9d90893](https://github.com/stevearc/oil.nvim/commit/9d90893c377b6b75230e4bad177f8d0103ceafe4))

## [1.1.0](https://github.com/stevearc/oil.nvim/compare/v1.0.0...v1.1.0) (2023-08-09)


### Features

* config to remove icon padding ([#145](https://github.com/stevearc/oil.nvim/issues/145)) ([b24380c](https://github.com/stevearc/oil.nvim/commit/b24380c0e17d21271cc04d94827a07397b9fc4dc))


### Bug Fixes

* directory hijacking when oil is lazy loaded ([#149](https://github.com/stevearc/oil.nvim/issues/149)) ([966eaaa](https://github.com/stevearc/oil.nvim/commit/966eaaadbc4d344660f867e41f6b1252459065b2))
* leave netrw autocmds intact when default_file_explorer = false ([#135](https://github.com/stevearc/oil.nvim/issues/135)) ([789b486](https://github.com/stevearc/oil.nvim/commit/789b486fb5cdc9e31abe9b0569b0e316f9d07bfd))
* opening oil from netrw defaults to netrw directory ([#148](https://github.com/stevearc/oil.nvim/issues/148)) ([887bb4a](https://github.com/stevearc/oil.nvim/commit/887bb4a8b6c9d73db9c34352d5363ee6289f733e))
* previewed buffers are deleted once hidden ([#141](https://github.com/stevearc/oil.nvim/issues/141)) ([eaa20a6](https://github.com/stevearc/oil.nvim/commit/eaa20a6aee7c4df89d80ec8208de63ec2fa4d38a))
* url-escape paths for scp ([#134](https://github.com/stevearc/oil.nvim/issues/134)) ([a5ff72a](https://github.com/stevearc/oil.nvim/commit/a5ff72a8da0df1042ee4c7705c301901062fa6d5))
* use standard Directory highlight group ([#139](https://github.com/stevearc/oil.nvim/issues/139)) ([f180a9f](https://github.com/stevearc/oil.nvim/commit/f180a9ffab24946a933621108144e2901533d583))

## 1.0.0 (2023-06-27)


### ⚠ BREAKING CHANGES

* selecting multiple files only opens buffers, not windows ([#111](https://github.com/stevearc/oil.nvim/issues/111))
* make oil buffers unlisted by default ([#45](https://github.com/stevearc/oil.nvim/issues/45))
* change scp:// urls back to oil-ssh://

### Features

* action to copy path to entry under cursor ([#50](https://github.com/stevearc/oil.nvim/issues/50)) ([6581d76](https://github.com/stevearc/oil.nvim/commit/6581d76a74760be5fcc5ca562d5032dcba7e5d9a))
* action to open entry in new tab ([#52](https://github.com/stevearc/oil.nvim/issues/52)) ([48eec8b](https://github.com/stevearc/oil.nvim/commit/48eec8b7ef67a5d7a50869fedf0ebbc82a8183d7))
* action to open the cmdline with current entry as argument ([#38](https://github.com/stevearc/oil.nvim/issues/38)) ([75b710e](https://github.com/stevearc/oil.nvim/commit/75b710e311104bc51eb5d04d1ac5db5193f7e834))
* add `setup.view_options.is_excluded` ([19ab948](https://github.com/stevearc/oil.nvim/commit/19ab948e25825a1b8823a391b733cc461f3010f7))
* add action to open a terminal ([c6a2e3e](https://github.com/stevearc/oil.nvim/commit/c6a2e3e08f1f70e52bbfff2b52093c779b4f24ed))
* add bug_report template ([23d1ca7](https://github.com/stevearc/oil.nvim/commit/23d1ca7327413973bbf7aee09e9f25b6f887f370))
* add override config option to customize float layout ([#132](https://github.com/stevearc/oil.nvim/issues/132)) ([ac72a8d](https://github.com/stevearc/oil.nvim/commit/ac72a8df4afc1a543624c0eb1ebc0bedeb83c1a6))
* add toggle_float function ([#94](https://github.com/stevearc/oil.nvim/issues/94)) ([82c7068](https://github.com/stevearc/oil.nvim/commit/82c706822bb13a8ea7a21e0e3dccc83eaf40bfbc))
* added command ([af59e7b](https://github.com/stevearc/oil.nvim/commit/af59e7b53df66192d18170e56f018cbc736dd67f))
* API to change config.view.is_hidden_file at runtime ([#69](https://github.com/stevearc/oil.nvim/issues/69)) ([12bea0f](https://github.com/stevearc/oil.nvim/commit/12bea0f6466661b89a6293c090a415ad7a32d4c8))
* builtin support for editing files over ssh ([#27](https://github.com/stevearc/oil.nvim/issues/27)) ([ca4da68](https://github.com/stevearc/oil.nvim/commit/ca4da68aaebaebf5cd68151c2b5ad56e00c06126))
* can cancel out of progress window ([273c2ce](https://github.com/stevearc/oil.nvim/commit/273c2cecbfe3ddc9fc19446f59cc6e7ff8981cf2))
* can minimize the progress window ([f28e634](https://github.com/stevearc/oil.nvim/commit/f28e63460ae23d88ecca8ba7bb4201b682692bee))
* **columns:** Add compatibility with previous versions ([98a186e](https://github.com/stevearc/oil.nvim/commit/98a186e8f9bd12621f988e95e8dbc4c67f0f3167))
* **columns:** Change to use custom icons ([6dc65dc](https://github.com/stevearc/oil.nvim/commit/6dc65dcf83dbd68a031d848dde61d104e6209b0c))
* config for floating preview window ([#74](https://github.com/stevearc/oil.nvim/issues/74)) ([3e1affa](https://github.com/stevearc/oil.nvim/commit/3e1affa6c784ce6911895a63232fa6e1a6ff5b70))
* config function to define which files are hidden ([#58](https://github.com/stevearc/oil.nvim/issues/58)) ([e5acff1](https://github.com/stevearc/oil.nvim/commit/e5acff1b77ff4372c94ace7daec21f93810166f7))
* config option for trashing deleted files ([#99](https://github.com/stevearc/oil.nvim/issues/99)) ([496d60f](https://github.com/stevearc/oil.nvim/commit/496d60fcff7af652e67c217aa82ab8d219a3f54e))
* config option to disable directory hijacking ([#76](https://github.com/stevearc/oil.nvim/issues/76)) ([3d3df74](https://github.com/stevearc/oil.nvim/commit/3d3df74532eaea2b071da03079c3a4c8e4fe5aeb))
* config option to skip the disclaimer ([adff3b9](https://github.com/stevearc/oil.nvim/commit/adff3b91541cde52793e41b34338f1f9cc19b3a6))
* **config:** Add custom icons ([bf20bca](https://github.com/stevearc/oil.nvim/commit/bf20bca78ddae7fd98ba98046014f3b06c8352ce))
* **config:** Change custom icons to columns config ([cb54e03](https://github.com/stevearc/oil.nvim/commit/cb54e034905ea67c7dd20008952203f0f7b4ed08))
* convert oil://path/to/file.lua to normal file path ([#77](https://github.com/stevearc/oil.nvim/issues/77)) ([d7805c7](https://github.com/stevearc/oil.nvim/commit/d7805c77515082d9e287feb010b3132dde838b3d))
* dispatch autocmd when oil buffer finishes rendering ([3ac035e](https://github.com/stevearc/oil.nvim/commit/3ac035e5ac448ce898c9aad7158a47378be4e85a))
* display shortened path as title of floating window ([#12](https://github.com/stevearc/oil.nvim/issues/12)) ([9f7c4d7](https://github.com/stevearc/oil.nvim/commit/9f7c4d74e1fefc7d88ff5094027b447eadecd787))
* expose buf_options in config ([#28](https://github.com/stevearc/oil.nvim/issues/28)) ([997d9cd](https://github.com/stevearc/oil.nvim/commit/997d9cd78a512d940e3a329e2746d20d77285189))
* extension for resession.nvim ([2bca582](https://github.com/stevearc/oil.nvim/commit/2bca582d935b723e67a41ec8c2d00684a3d1fc8a))
* first draft ([fefd6ad](https://github.com/stevearc/oil.nvim/commit/fefd6ad5e48ff5fcd04fa76d1410a65c40376964))
* inform user how to disable netrw ([6b10a36](https://github.com/stevearc/oil.nvim/commit/6b10a366414578022165fb1e2effea6362bf8ced))
* more actions for interacting with preview window ([#41](https://github.com/stevearc/oil.nvim/issues/41)) ([b3c4ff3](https://github.com/stevearc/oil.nvim/commit/b3c4ff340bed8bb88dc87f054334d67e47aae492))
* new action open_cmdline_dir ([#44](https://github.com/stevearc/oil.nvim/issues/44)) ([6c4a3da](https://github.com/stevearc/oil.nvim/commit/6c4a3dafcadec5f6818135e11c27250a9bdcbbff))
* Oil command supports split and vert modifiers ([#116](https://github.com/stevearc/oil.nvim/issues/116)) ([f322209](https://github.com/stevearc/oil.nvim/commit/f322209a4a2b4685adeda5df00b29cdfd64db08e))
* oil.select can close oil buffer afterwards ([#121](https://github.com/stevearc/oil.nvim/issues/121)) ([a465123](https://github.com/stevearc/oil.nvim/commit/a4651236594cd7717c9b75c43ede0ed5fd4a7dc9))
* option to disable all default keymaps ([#16](https://github.com/stevearc/oil.nvim/issues/16)) ([28da68a](https://github.com/stevearc/oil.nvim/commit/28da68ac5ca451a1f882ecc1eb720295e8c8fd51))
* prompt user to save changes before editing moved file/dir ([#93](https://github.com/stevearc/oil.nvim/issues/93)) ([6b05c2e](https://github.com/stevearc/oil.nvim/commit/6b05c2e91378960be7f7e73867112cee0b4a408a))
* restore window view in oil.close() ([#65](https://github.com/stevearc/oil.nvim/issues/65)) ([33ee724](https://github.com/stevearc/oil.nvim/commit/33ee724c2d25358917147718c3b108a90b571e20))
* set filetype='oil_preview' for preview buffer ([a587977](https://github.com/stevearc/oil.nvim/commit/a587977edda67fd6f506da11e55e3c27727df646))
* sort symbolic directory links like directories ([98fcc2d](https://github.com/stevearc/oil.nvim/commit/98fcc2d0d77f16941d5aac2e0dcf4cffd3cf699a))
* support custom trash commands ([#110](https://github.com/stevearc/oil.nvim/issues/110)) ([f535c10](https://github.com/stevearc/oil.nvim/commit/f535c1057c8d7ce2865bfff1881cc99aa726a044))
* update preview window when cursor is moved ([#42](https://github.com/stevearc/oil.nvim/issues/42)) ([6c6b767](https://github.com/stevearc/oil.nvim/commit/6c6b7673af1314dd7c8254a95eb8d331f6b76ac6))
* Use &lt;C-l&gt; to refresh directory ([#7](https://github.com/stevearc/oil.nvim/issues/7)) ([d019d38](https://github.com/stevearc/oil.nvim/commit/d019d38a3ef4926308735a00bd919a5666c464b6))


### Bug Fixes

* add autocmd to augroup ([5e2f1ce](https://github.com/stevearc/oil.nvim/commit/5e2f1ced9fae1b1dfec45f11f42d49ac9e299bc2))
* add WinLeave autocmd to augroup ([6a227e9](https://github.com/stevearc/oil.nvim/commit/6a227e932fb5e5cac9d4c0fef2a500cac047e99e))
* allow calling oil.open() with a url ([be695dc](https://github.com/stevearc/oil.nvim/commit/be695dc3502f8fb052a83720f3a4dd9578cacdf0))
* alternate buffer preservation ([#43](https://github.com/stevearc/oil.nvim/issues/43)) ([4e853ea](https://github.com/stevearc/oil.nvim/commit/4e853eabcb002650096ef78f098253fe12ba3d8f))
* always close keymap help window ([#17](https://github.com/stevearc/oil.nvim/issues/17)) ([7b703b4](https://github.com/stevearc/oil.nvim/commit/7b703b42da815fb280c6fd7b73961c2e87bcff07))
* always enter directory entries as a directory ([0d5db08](https://github.com/stevearc/oil.nvim/commit/0d5db08015d41a0e3da727bf70796f3a4abcfa76))
* another case of incorrect alternate buffers ([#60](https://github.com/stevearc/oil.nvim/issues/60)) ([b36ba91](https://github.com/stevearc/oil.nvim/commit/b36ba91b7a4d05ee43617383f68cf6ed6fc2f08e))
* bad interaction with editorconfig-vim ([7371dd2](https://github.com/stevearc/oil.nvim/commit/7371dd220f1d08789cc225846d8cafed938777e9))
* better behaved lazy loading in autocmds ([7f17648](https://github.com/stevearc/oil.nvim/commit/7f176487052a155d43c6b64ef44b6dd775e94f99))
* block quit if changes during :wq ([#98](https://github.com/stevearc/oil.nvim/issues/98)) ([37cb6be](https://github.com/stevearc/oil.nvim/commit/37cb6be6f6f98c4616ca382ad955c709dc38f39d))
* bug when copying saved win options to split ([#89](https://github.com/stevearc/oil.nvim/issues/89)) ([caa65e5](https://github.com/stevearc/oil.nvim/commit/caa65e5bfcc98a1450f6a5659fe0f4d28a311967))
* catch errors opening preview window ([#113](https://github.com/stevearc/oil.nvim/issues/113)) ([64d2f30](https://github.com/stevearc/oil.nvim/commit/64d2f305d30cec13938aa99f8f13bd84c502e020))
* close floating oil window on WinLeave ([#17](https://github.com/stevearc/oil.nvim/issues/17)) ([0f10485](https://github.com/stevearc/oil.nvim/commit/0f104854dab0b9edc9dd90bb70fdd782568283ef))
* copying symlinks ([dc18d06](https://github.com/stevearc/oil.nvim/commit/dc18d06bcbf02d84ed48cfa250582c0bb7aa6a02))
* detect duplicate filenames in buffer ([bcb99ae](https://github.com/stevearc/oil.nvim/commit/bcb99ae95a349d33dac9ea54dff0f8915e567eec))
* don't close floating windows we didn't open ([#64](https://github.com/stevearc/oil.nvim/issues/64)) ([073ecb3](https://github.com/stevearc/oil.nvim/commit/073ecb3d68580cd131cd30d83163576807172a77))
* don't show preview if there are no changes ([#19](https://github.com/stevearc/oil.nvim/issues/19)) ([6d0b6ac](https://github.com/stevearc/oil.nvim/commit/6d0b6ac43ce368e5d7aca1798339b597ef6c9981))
* double callback in mutator ([0046508](https://github.com/stevearc/oil.nvim/commit/00465089cb4fdf2c9fb491cd63e36ca135ac6291))
* edge case where cursor position was not set ([#37](https://github.com/stevearc/oil.nvim/issues/37)) ([64d7763](https://github.com/stevearc/oil.nvim/commit/64d7763ac69c581bf1c28492994567c05ddff28a))
* edge case where opening a file would delete its contents ([2e95b9d](https://github.com/stevearc/oil.nvim/commit/2e95b9d42467168185cc5a505ef4288de4c5670f))
* edge case where window options were not set ([b8eaf88](https://github.com/stevearc/oil.nvim/commit/b8eaf88c127b7807fa3a8b00be881ab94f5168b3))
* error messages opening terminal in dir ([90acbdb](https://github.com/stevearc/oil.nvim/commit/90acbdbbffcb461bc6de3544bf8b695f7abeb168))
* error when editing a dir, and still missing parent window ([#40](https://github.com/stevearc/oil.nvim/issues/40)) ([a688443](https://github.com/stevearc/oil.nvim/commit/a6884431b0d7adccf9f4756ca543bf175052f742))
* error when float border is 'none' ([#125](https://github.com/stevearc/oil.nvim/issues/125)) ([4ad1627](https://github.com/stevearc/oil.nvim/commit/4ad162756b800fee4542726b48e98125fb5d7913))
* Error when saving blank lines and quitting. ([2bc63f7](https://github.com/stevearc/oil.nvim/commit/2bc63f7059050f6b172be6aea0402e8b177bde58))
* error when use_default_keymaps = false ([#56](https://github.com/stevearc/oil.nvim/issues/56)) ([f1ea6e0](https://github.com/stevearc/oil.nvim/commit/f1ea6e0ad03e1d7b1acad4d0796d39c4a82b3463))
* escape special characters when editing buffer ([#96](https://github.com/stevearc/oil.nvim/issues/96)) ([339ade9](https://github.com/stevearc/oil.nvim/commit/339ade9dc387958c714a98741cda9e722a931410))
* expand terminal path ([20e4ff1](https://github.com/stevearc/oil.nvim/commit/20e4ff1838d384141f6252520ae572a63abff2cd))
* float positioning and width calculation ([#32](https://github.com/stevearc/oil.nvim/issues/32)) ([f8ca564](https://github.com/stevearc/oil.nvim/commit/f8ca5648021ac6a59e016d81be594fa98f0705c2))
* guard against invalid buffer ([#90](https://github.com/stevearc/oil.nvim/issues/90)) ([a9556aa](https://github.com/stevearc/oil.nvim/commit/a9556aa872215f5956062f24064ade55cf2baeb9))
* icon column does nil-check of config ([f6d2102](https://github.com/stevearc/oil.nvim/commit/f6d2102e2b671ffe28029c0b4b0915e625c3f09f))
* ignore errors when unlocking buffers ([e58f347](https://github.com/stevearc/oil.nvim/commit/e58f347c674332d2ece6a0ff6da05cf93bf0f0b9))
* invalid filetype of oil buffer ([#47](https://github.com/stevearc/oil.nvim/issues/47)) ([2b0b938](https://github.com/stevearc/oil.nvim/commit/2b0b9382d77c4a9ff471a999bddb2f9cc945a300))
* more detailed information when ssh connection fails ([#27](https://github.com/stevearc/oil.nvim/issues/27)) ([f5961e7](https://github.com/stevearc/oil.nvim/commit/f5961e731f641206727eaded197e5879694c35f7))
* new oil buffers are nomodifiable during mutation processing ([d631d9f](https://github.com/stevearc/oil.nvim/commit/d631d9fc5a958c7c9ee0717b1fe040a3ec951c63))
* no error if opening file that has swapfile ([a60639d](https://github.com/stevearc/oil.nvim/commit/a60639db358c0b40f9fe297b1f52f3eb62c190c6))
* off-by-one errors in tests ([6062ad6](https://github.com/stevearc/oil.nvim/commit/6062ad6737d36e8a1cc10696cf5e870057eba20c))
* oil buffers load properly after loading a session ([#29](https://github.com/stevearc/oil.nvim/issues/29)) ([bb5201c](https://github.com/stevearc/oil.nvim/commit/bb5201c9cd422e7b145699b5dccd8e70e4630a9d))
* oil buffers remain unmodified after saving changes ([931453f](https://github.com/stevearc/oil.nvim/commit/931453fc09085c09537295c991c66637869e97e1))
* oil can open when terminal is focused ([#51](https://github.com/stevearc/oil.nvim/issues/51)) ([0e53d40](https://github.com/stevearc/oil.nvim/commit/0e53d402219c74d351fffb18d97d7e350f87bfd8))
* oil loses track of buffers after refresh ([9871ca9](https://github.com/stevearc/oil.nvim/commit/9871ca9737d4ffd68b40ad68b8f89848d835b286))
* oil-ssh assume target machine's locales ([c72bcb4](https://github.com/stevearc/oil.nvim/commit/c72bcb45b2e824150cbf356c2e13e37d6863369b))
* oil.close doesn't error when no other buffers exist ([#79](https://github.com/stevearc/oil.nvim/issues/79)) ([4b05ebd](https://github.com/stevearc/oil.nvim/commit/4b05ebdf202bf61ce240f40558822fe5564d02ea))
* oil.close() sometimes closes window too ([#64](https://github.com/stevearc/oil.nvim/issues/64)) ([d48fa09](https://github.com/stevearc/oil.nvim/commit/d48fa09c82b133d384c84c98725b722fd06f38af))
* opening with lowercase drive letters ([29808f2](https://github.com/stevearc/oil.nvim/commit/29808f273c817543d049f6d2541a550e233de4ff))
* preserve alternate buffer when using floating window ([#20](https://github.com/stevearc/oil.nvim/issues/20)) ([d8a1e7c](https://github.com/stevearc/oil.nvim/commit/d8a1e7ca4e599c43dda1849a66b19d9fbff12310))
* preserve the alternate buffer ([#20](https://github.com/stevearc/oil.nvim/issues/20)) ([e4c4110](https://github.com/stevearc/oil.nvim/commit/e4c411002272d6eed159afdf4cae2e74dc7fc813))
* prevent double-delete autocmd ids ([#97](https://github.com/stevearc/oil.nvim/issues/97)) ([4107784](https://github.com/stevearc/oil.nvim/commit/41077847b98d6d3b88b6d31864bb20a664e88574))
* preview window renders on top of floating window title ([#72](https://github.com/stevearc/oil.nvim/issues/72)) ([383971b](https://github.com/stevearc/oil.nvim/commit/383971b0cfd8248ec3d00d4a3154d69ebd5e394e))
* renaming buffers doesn't interfere with directory hijack ([#25](https://github.com/stevearc/oil.nvim/issues/25)) ([b4ccc16](https://github.com/stevearc/oil.nvim/commit/b4ccc16944a3678558ab8f73fa803409b38f58d6))
* reposition preview window if vim is resized ([8cbb104](https://github.com/stevearc/oil.nvim/commit/8cbb104e76efee35ca8125da8d441c395e568e23))
* reposition progress window if vim is resized ([092f4b1](https://github.com/stevearc/oil.nvim/commit/092f4b1c7c14633cd58659dc93eed92c5c26810c))
* restore modified state of current buffer if actions are canceled ([#6](https://github.com/stevearc/oil.nvim/issues/6)) ([2e6d684](https://github.com/stevearc/oil.nvim/commit/2e6d68453f98d3d69cd5c36577f7a381aa7399f3))
* restore window options on split windows ([#36](https://github.com/stevearc/oil.nvim/issues/36)) ([fb69775](https://github.com/stevearc/oil.nvim/commit/fb697752b28ecc41ecaab4206b41e61496ab87f2))
* selecting multiple files only opens buffers, not windows ([#111](https://github.com/stevearc/oil.nvim/issues/111)) ([393f0dc](https://github.com/stevearc/oil.nvim/commit/393f0dcf82f04de597e194ec120d8cbe6fe212a8))
* set alternate buffer when inside oil ([#60](https://github.com/stevearc/oil.nvim/issues/60)) ([f1131b5](https://github.com/stevearc/oil.nvim/commit/f1131b5e90ce5cdbbd122e298d62726dfa4b808a))
* set bufhidden = 'hide' by default ([#104](https://github.com/stevearc/oil.nvim/issues/104)) ([19563c3](https://github.com/stevearc/oil.nvim/commit/19563c365800ab519e46a08a0aa59d5677b329b6))
* shortened path for current directory is '.' ([7649866](https://github.com/stevearc/oil.nvim/commit/76498666500c2aee94fd07366222d76c4d13ee2f))
* silence doautocmd errors ([9dbf18a](https://github.com/stevearc/oil.nvim/commit/9dbf18a524df1a563b2a8f46b14645aa47022f9e))
* some autocmds skipped when opening files from oil ([#120](https://github.com/stevearc/oil.nvim/issues/120)) ([61f8655](https://github.com/stevearc/oil.nvim/commit/61f8655e03dea805bb77aad5b4ca99d1176510b7))
* ssh adapter handles character and block files ([aa68ec4](https://github.com/stevearc/oil.nvim/commit/aa68ec4d988be3c898341f65f54c1620986240dd))
* stop using vim.wo to set window options ([6f8bf06](https://github.com/stevearc/oil.nvim/commit/6f8bf067c09e96d6bff548b5e6addb6d9c25a678))
* symbolic link target parsing fails if it has a trailing slash ([#131](https://github.com/stevearc/oil.nvim/issues/131)) ([9be36a6](https://github.com/stevearc/oil.nvim/commit/9be36a648889c37d11bc65e8422049dc33dd6a3f))
* unexpected behavior from BufReadPost autocmds ([716dd8f](https://github.com/stevearc/oil.nvim/commit/716dd8f9cf1ff2b9cda03497025612ce3c366307))
* unlock buffers if we cancel the actions ([#4](https://github.com/stevearc/oil.nvim/issues/4)) ([0d6ee14](https://github.com/stevearc/oil.nvim/commit/0d6ee144d210b8627e9c3fd98dc32ec3e9360aa2))
* update preview window in-place ([#74](https://github.com/stevearc/oil.nvim/issues/74)) ([57451c5](https://github.com/stevearc/oil.nvim/commit/57451c517d96ad856ed418203729f5d3cb200de6))
* url formatting errors when ssh connection specifies port ([9a03af7](https://github.com/stevearc/oil.nvim/commit/9a03af7cb752f46b9efa85fc132d9281f5672f23))
* warning when :tabnew from oil buffer ([#40](https://github.com/stevearc/oil.nvim/issues/40)) ([73c6fcf](https://github.com/stevearc/oil.nvim/commit/73c6fcf519afbd99b8cef00d8663bed20f87a1df))


### Code Refactoring

* change scp:// urls back to oil-ssh:// ([3164537](https://github.com/stevearc/oil.nvim/commit/31645370a105e59270634ec14665149e919f7432))
* make oil buffers unlisted by default ([#45](https://github.com/stevearc/oil.nvim/issues/45)) ([1d54819](https://github.com/stevearc/oil.nvim/commit/1d548190cf4a032d0354c0bf84d042a618152769))
