node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com/', 'sabhishekdockerhub') {

        def customImage = docker.build("sabhishek1107/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
