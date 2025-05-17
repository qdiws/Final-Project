# Developer Documentation

## How to Install
```
cd client
npm install
cd ../server
npm install
```

## How to Run
```
# In one terminal
cd server
npm start

# In another terminal
cd client
npm start
```

## How to Test
```
# Frontend test
cd client
npm test

# Backend test
cd server
npm test
```

## API Reference
**GET /api/matchmaking/:userId** – Returns suggested teammates

**POST /api/users** – Creates user profile

**POST /api/verify-phone** – Validates phone number using Numverify API

## Known Bugs
- Some country codes fail verification
- Matching doesn’t factor communication preferences yet

## Roadmap
- Add ratings for teammates
- Add Discord ID / contact sharing
- In-app voice communication
