# [pop](http://popy.herokuapp.com/) [![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/kumabotz/pop/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

![](https://raw.github.com/kumabotz/pop/master/game.png)

## Setup [![Hack kumabotz/pop on Nitrous.IO](https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-s-v1-7475db0cf93fe5d1e29420c928ebc614.png)](https://www.nitrous.io/hack_button?source=embed&runtime=rails&repo=kumabotz%2Fpop&file_to_open=README.md)

You'll need these installed in your box:

1. Ruby 2.1.2 (or higher): use [RVM](https://rvm.io/)
   - `curl -L https://get.rvm.io | bash -s stable`
   - `rvm install 2.1.2`
   - `rvm use 2.1.2 --default`
1. bundler: `gem install bundler --no-ri --no-rdoc`

And then do these:

1. Setup RVM project file: `rvm --ruby-version use 2.1.2@pop --create`
1. Install gem dependencies: `bundle install`
1. Run the :star2: Rails app: `bundle exec rails s`

## TODO
- [x] Convert into [rails app](http://popy.herokuapp.com/)
- [x] Deploy to [heroku](http://popy.herokuapp.com/)
- [x] Add nitrous [HACK button](https://www.nitrous.io/hack_button?source=embed&runtime=rails&repo=kumabotz%2Fpop&file_to_open=README.md)
- [ ] Use [BEM](http://bem.info/)
- [ ] Update JS architecture
- [ ] Setup tests
- [ ] Responsive layout ([foundation](http://foundation.zurb.com/))

## References
- [How To Design A Mobile Game With HTML5](http://mobile.smashingmagazine.com/2012/10/19/design-your-own-mobile-game/)
- [Ruby on Rails Tutorial](http://www.railstutorial.org/book)
