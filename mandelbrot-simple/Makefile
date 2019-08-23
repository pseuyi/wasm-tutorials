export EMCC_DEBUG=1

mandelbrot.js: mandelbrot.cpp
	emcc --bind --std=c++11 mandelbrot.cpp -s WASM=1 -s ALLOW_MEMORY_GROWTH=1

clean:
	rm *.js *.wasm
