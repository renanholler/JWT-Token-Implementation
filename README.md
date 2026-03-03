<div>
  <image height="32em" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <image height="32em" src="http://jwt.io/img/logo-asset.svg" />
  <image height="32em" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
</div>

## Project Structure

The project is composed of the following files:

1. **generateSignature.ts**: Contains the `generateSignature` function responsible for generating the token signature.
2. **sign.ts**: Exports the `sign` function, which creates a signed JWT token based on the provided data.
3. **verify.ts**: Exports the `verify` function, which validates and decodes a JWT token.

## How to Use

### Installation

Make sure you have Node.js and TypeScript installed. Clone the repository and install the dependencies:
```bash
git clone https://github.com/renanholler/JWT-Token-Implementation.git
cd JWT-Token-Implementation
npm install
```
