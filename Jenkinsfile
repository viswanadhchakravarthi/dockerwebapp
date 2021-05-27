node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DockerHub') {

        def customImage = docker.build("viswa2000/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
