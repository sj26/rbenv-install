# rbenv-install

A pretty thin wrapper around [ruby-build](https://github.com/sstephenson/ruby-build) for [rbenv](https://github.com/sstephenson/rbenv) (you'll need both).

Put `bin/rbenv-install` in your `PATH` somewhere, then:

    $ rbenv install

You'll get something like:

    Install a ruby using ruby-build, i.e.
        rbenv install 1.9.2-p290
    or, if so inclined, install all rubies:
        rbenv install --all

    Available rubies:
    1.8.7-p352
    1.9.2-p290
    1.9.3-preview1
    jruby-1.6.3
    rbx-1.2.4
    ree-1.8.7-2011.03

Then:

    $ rbenv install ree-1.8.7-2011.03
    Downloading ... ...

Hooray!

## License

(The MIT license)

Copyright (c) 2011 Samuel Cochran

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
