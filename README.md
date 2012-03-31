This is a sample of scalatra on heroku 

# Debug on Eclipse

1. Import to Eclipse

2. Debug As >  Scala Application src/main/scala/JettyLauncher.scala 

3. Go to http://localhost:8080/.

4. Learn more at http://www.scalatra.org/stable/book.

5. Happy hacking!


# Debug on console

1. Launch [SBT](http://code.google.com/p/simple-build-tool).

        ./sbt

2. Run Jetty

        container:start

3. Go to http://localhost:8080/.

4. Learn more at http://www.scalatra.org/stable/book.

5. Happy hacking!


# Deploy to heroku

```sh
$ heroku login
$ heroku create --stack cedar
$ git push heroku master
```

# Other deplying

See http://www.scalatra.org/2.0/book/#Production_Deployment
