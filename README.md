# Beautiful Apache urls with languages
Pretty URLs with language GET parameter using .htaccess on Apache servers

The `.htaccess` file configures the Apache HTTP server to obtain beautiful and ordered URLs
with default behaviors for file extension, trailing slash and initial `www`.

It is also useful to manage multi-language pages with virtual language code after the domain,
with the language code being passed as a GET parameter to the page.
For a discussion on the argument see https://support.google.com/webmasters/answer/182192

E.g. of redirections:
```
domain.com  =>  www.domain.com
www.domain.com/file/  =>  www.domain.com/file
www.domain.com/directory  =>  domain.com/directory/
www.domain.com/index  =>  www.domain.com
```

E.g. of resolutions:
```
www.domain.com/page  =>  www.domain.com/page.php
www.domain.com/en/page  =>  www.domain.com/page.php?lang=en
www.domain.com/it/directory/  =>  www.domain.com/directory/index.php?lang=it
```

## Author
* [Simone Donadello](https://github.com/simondona/) <simon.dona.dev@gmail.com>

## License
This code is licensed under the [Apache License, Version 2.0] (http://www.apache.org/licenses/LICENSE-2.0).
Feel free to use it.
```
Copyright 2016 Simone Donadello

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
