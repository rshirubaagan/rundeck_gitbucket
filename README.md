# Just a Rundeck + GitBucket environment to test SCM stuff

To run, clone the repository and then execute:

`docker compose up`

After a couple of minutes, Rundeck (and GitBucket) should be available, open your favorite browser (no IE please!) and access to `http://localhost:4440` URL, user: `admin`, password: `admin`.

To access the GitBucket instance, open another browser tab with the following URL: `http://localhost:8080` URL (user: `root`, password: `root`)

You can learn more about Rundeck [here](https://docs.rundeck.com/docs/about/introduction.html).

And learn more about SCM [here](https://docs.rundeck.com/docs/manual/projects/scm/git.html).

Cheers.
