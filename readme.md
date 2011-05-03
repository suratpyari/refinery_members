# members plugin for [RefineryCMS](http://www.refinerycms.com) ([Github](https://github.com/suratpyari/refinery_members))

By: [Surat Pyari]()

This Plugin allows you to add members to your application. 

## Requirements

This engine requires RefineryCMS version >= 0.9.9.16

## Gem Installation

Ensure you have created your application's database

Open your ``Gemfile`` and add this line to the bottom:

    gem 'refinerycms-member'

Now run:
		
		bundle install
    rails generate refinerycms_members
    rake db:migrate

Now you can see 'Members' tab after restarting your web server.