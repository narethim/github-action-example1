# github-action-example1

## Prerequisite

* Java code
* Gradle project

## Workflow

### build the project

    ./gradlew build

### build Docker image called java-app. Execute from root

   docker build -t java-app .

### push image to repo

    docker tag java-app demo-app:java-1.0

## References

* [GitHub Actions Tutorial - Basic Concepts and CI/CD Pipeline with Docker](https://www.youtube.com/watch?v=R8_veQiYBjI)

* [mr-smithers-excellent/docker-build-push](https://github.com/mr-smithers-excellent/docker-build-push)
