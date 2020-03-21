# Multi-Robot Decentralized Architecture

## Usage

Just run

 ```docker-compose up --build --force-recreate```

This fetches all the base images, builds containers and starts 1 Simulator, 3 Robot, 1 Google Cartographer Server containers. 

Have a look at  `docker-compose.yaml`  file for more info.

## Screenshots

### Gazebo Container
![Gazebo Container](/screenshots/Gazebo_Container.png)

### Robot Container
![Robot_Container](/screenshots/Robot_Container.png)

### Google Cartographer Cloud Container
![Google Cartographer Cloud Container](/screenshots/GC_Cloud_Container.png)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements
The basis for this architecture was [Ros-Simulation](https://github.com/microsoft/Ros-Simulation) project.

## License
[MIT](https://choosealicense.com/licenses/mit/)