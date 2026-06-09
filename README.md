<h2>RSA Cryptographic Tool – Project Description</h2>

<p>
The RSA Cryptographic Tool is a fully browser-based, client-side application designed
to perform RSA encryption and decryption using the RSA/ECB/PKCS1Padding algorithm.
The tool provides a secure environment for generating RSA key pairs, importing and
exporting PEM-formatted keys, encrypting plaintext messages, and decrypting ciphertext
without transmitting any data to external servers.
</p>

<h3>Key Features</h3>

<ul>
    <li>RSA/ECB/PKCS1 v1.5 Encryption and Decryption</li>
    <li>Client-side cryptographic processing with no server dependency</li>
    <li>RSA key pair generation with 1024, 2048, and 4096-bit key sizes</li>
    <li>Public and Private Key import/export in PEM format</li>
    <li>PKCS#1 v1.5 padding implementation</li>
    <li>Base64 and Hexadecimal ciphertext encoding options</li>
    <li>Multi-block message encryption support</li>
    <li>CRT (Chinese Remainder Theorem) optimized RSA decryption</li>
    <li>Dark Mode and Light Mode user interface</li>
    <li>Responsive design for desktop and mobile devices</li>
</ul>

<h3>Security Architecture</h3>

<p>
The application performs all cryptographic operations directly inside the browser
using JavaScript and the Web Crypto random number generator. No plaintext,
ciphertext, keys, or sensitive information are transmitted over the network,
ensuring complete privacy and data confidentiality.
</p>

<p>
RSA key generation is implemented using:
</p>

<ul>
    <li>Miller-Rabin probabilistic prime testing</li>
    <li>Cryptographically secure random number generation</li>
    <li>Modular arithmetic using JavaScript BigInt</li>
    <li>PKCS#1 v1.5 compliant encryption padding</li>
</ul>

<h3>Key Management Module</h3>

<p>
The tool includes a complete key management system that allows users to:
</p>

<ul>
    <li>Generate RSA key pairs</li>
    <li>View generated public and private keys</li>
    <li>Import existing PEM-formatted keys</li>
    <li>Export keys as downloadable PEM files</li>
    <li>Copy keys directly to the clipboard</li>
    <li>Clear keys securely from memory and the interface</li>
</ul>

<h3>Encryption Workflow</h3>

<ol>
    <li>Generate or import a public key.</li>
    <li>Enter plaintext data.</li>
    <li>Select the desired output format (Base64 or Hex).</li>
    <li>Execute encryption.</li>
    <li>Receive encrypted ciphertext output.</li>
</ol>

<h3>Decryption Workflow</h3>

<ol>
    <li>Generate or import a private key.</li>
    <li>Paste encrypted ciphertext.</li>
    <li>Execute decryption.</li>
    <li>Recover the original plaintext message.</li>
</ol>

<h3>User Interface Components</h3>

<ul>
    <li>Modern cryptography-focused dashboard</li>
    <li>Key generation and management panel</li>
    <li>Encryption and decryption mode selector</li>
    <li>Input and output workspace</li>
    <li>Encoding format switcher</li>
    <li>Real-time status monitoring panel</li>
    <li>Toast notifications and validation messages</li>
    <li>Theme toggle (Dark/Light Mode)</li>
</ul>

<h3>Technical Implementation</h3>

<ul>
    <li>Single self-contained HTML file</li>
    <li>Pure JavaScript implementation</li>
    <li>No external cryptographic libraries</li>
    <li>BigInt-based RSA arithmetic engine</li>
    <li>ASN.1 DER encoding and decoding support</li>
    <li>PKCS#8 public/private key handling</li>
    <li>Responsive CSS design system</li>
</ul>

<h3>Use Cases</h3>

<ul>
    <li>Testing RSA encryption and decryption flows</li>
    <li>Educational cryptography demonstrations</li>
    <li>Secure message encryption experiments</li>
    <li>PEM key generation and validation</li>
    <li>Offline cryptographic operations</li>
    <li>Developer and security research activities</li>
</ul>

<h3>Conclusion</h3>

<p>
The RSA Cryptographic Tool is a comprehensive, secure, and user-friendly web
application that enables RSA key management, encryption, and decryption entirely
within the browser. By combining a modern interface with robust cryptographic
functionality, the project serves as both a practical utility and an educational
platform for understanding RSA public-key cryptography.
</p>
