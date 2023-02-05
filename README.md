# MongoDB and Express tutorial

This is a project I did while following Brad Traversy's course on the [mern stack](https://www.youtube.com/watch?v=-0exw-9YJBo&list=PLillGF-RfqbbQeVSccR9PGKHzPJSWqcsm)

## Getting started

1. Ensure you have yarn installed

   ```sh
   npm install -g yarn
   ```

2. Install the required packages
   ```sh
   yarn
   ```
3. Run the dev server using nodemon
   ```sh
   yarn dev
   ```

### Config

The following environmental variables are needed to ensure the app works correctly. In the root of the project create an `.env` file with the following values:

```
NODE_ENV = development
PORT = 5000
MONGO_URI=<mongodb uri>
JWT_SECRET=<your own secret>
```

# Credits

Thanks to Brad for an awesome tutorial. Links to his youtube channel and the tutorial:

- [Traversy Media](https://www.youtube.com/@TraversyMedia)
- [learn the MERN Stack](https://www.youtube.com/watch?v=-0exw-9YJBo&list=PLillGF-RfqbbQeVSccR9PGKHzPJSWqcsm)
