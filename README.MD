# Building CircleCI Container

## From the command line:

    docker build . -t ci_python3_node

## Re-build, i.e. to update the sentry sek

    docker build --no-cache . -t ci_python3_node

## Run Some stuff in there

    docker run -it -t ci_python3_node /bin/bash

## Now, to push to remote?

    git add -u
    git commit -m 'Message here'
    git push
    git tag # get list of tags
    git tag 1.1.1 && git push --tags





