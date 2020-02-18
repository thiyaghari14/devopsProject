node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("thiyagu14/webapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
