Advanced Multi-Texture Terrain Blending Shader with Anti-Tiling

Inspired by the https://godotshaders.com/shader/seamless-texture-sampler-without-repeating-patterns-tiling/
and https://iquilezles.org/articles/texturerepetition/


- Multi-Texture Support : Seamlessly blend up to 2 complete texture sets (albedo, normal, roughness, AO, height maps)

- Advanced Noise-Based Blending : Intelligent texture mixing using procedural noise patterns

- Superior Interpolation : Replaces simple smoothstep with quintic Hermite interpolation for ultra-smooth transitions

- Multi-Layer Domain Warping : Employs multiple layers of domain distortion noise for natural, organic texture distribution

- Fractal Noise Mixing : Combines multiple noise octaves to eliminate any trace of repetitive patterns

- High-Quality Hash Functions : Uses advanced mathematical constants and prime offsets to ensure truly random sampling

- Flexible Configuration : Adjustable texture scaling, noise intensity, blend sharpness, and UV rotation parameters



- Perlin-style gradient noise with complete grid artifact elimination

- Non-integer frequency sampling (1.31, 1.73, 2.17) to break periodicity

- Three-layer domain warping with independent offset vectors

- Smart texture validation and transparent handling for disabled textures

- Optimized performance with intelligent mipmap usage