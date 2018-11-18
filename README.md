### ramaze
---
http://ramaze.net/

https://github.com/Ramaze/ramaze

```
gem install ramaze
ruby hello_ramaze.rb
```

```ruby
require 'ramaze'
class MyController < Ramaze::Controller
  map '/'
  def index
    return "Hello!"
  end
end
Ramaze.start

```

```
```


