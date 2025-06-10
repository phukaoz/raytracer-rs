# raytracer-rs

A fast, educational, multithreaded ray tracer implemented in safe Rust 🚀  
Inspired by Peter Shirley's *Ray Tracing in One Weekend* book series.

## 🔧 Features
- Scene with spheres, planes, and materials
- Diffuse, metallic, and glassy surfaces
- Recursive ray tracing with multiple bounces
- Anti-aliasing and camera field-of-view
- Full CPU parallelism using `rayon`
- Output in `.ppm` or `.png`

## 📚 Why
Practice Rust through a project involving math, performance, and memory safety — ideal for C++ developers transitioning to Rust.

## 🚀 Run
```bash
cargo run --release