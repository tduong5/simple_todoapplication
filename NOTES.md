# Initialize Go app
go mod init github.com/tduong5/go-react-application

# Install Fiber v2
go get -u github.com/gofiber/fiber/v2

# Client client app using Vite
yarn create vite client -- --template react-ts

# Install dependencies
yarn add @mantine/hooks @mantine/core swr @primer/octicons-react